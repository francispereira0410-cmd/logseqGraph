query-table:: true
#+BEGIN_QUERY
{:title "Next 365 Days"
 :query
 [:find ?d
  :where
  [(js/window.Date.) ?today]
  [(range 0 365) ?offset]
  [(js/Date. (+ (.getTime ?today) (* ?offset 86400000))) ?future]
  [(.toISOString ?future) ?iso]
  [(subs ?iso 0 10) ?d]]
 :result-transform
 (fn [result]
   (map (fn [r] (str "[[" (first r) "]]")) result))
}
#+END_QUERY

	-
	-
	-
	-
	-
	-
	-
-
-
-
-