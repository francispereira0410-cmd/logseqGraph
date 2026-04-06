title:: Logseq File Sync (highlights)
author:: [[ChatGPT]]
full-title:: "Logseq Sync Setup"
category:: #articles
url:: https://chatgpt.com/c/699f53b6-5500-8329-a8e2-203c016952ff
summary:: Move your main Logseq folder from your master laptop to a Google Drive folder set to mirror files. On both laptops, open Logseq from this synced Google Drive folder to keep data updated and avoid conflicts. Always close Logseq and wait for syncing to finish before switching devices to prevent data loss.
![](https://cdn.openai.com/chatgpt/share-og.png)

- Highlights first synced by [[Readwise]] [[Feb 26th, 2026]]
	- Pick the laptop with the most up-to-date Logseq data.
	  
	  Let’s call it **Laptop A**. ([View Highlight](https://read.readwise.io/read/01kjdv9rc3ajbxaqagz0ez51ya))
	- Download:  
	  [https://www.google.com/drive/download/](https://www.google.com/drive/download/)
	  
	  During setup choose:
	  
	  > ✅ **Mirror files** (NOT Stream files)
	  
	  **Why mirror?**
	  
	  •   Mirror = Full local copy stored on disk
	    
	  •   Stream = Cloud-only until opened (can cause Logseq issues) ([View Highlight](https://read.readwise.io/read/01kjdv9120k4a2w2rtn5bpe2yq))
	- On Laptop A:
	  
	  1.  Close Logseq completely.
	    
	  2.  Move:
	    
	  
	  Code
	  
	  C:\Users\percl\logseq
	  
	  to:
	  
	  Code
	  
	  G:\My Drive\Logseq
	  
	  (or wherever your Drive mirror folder is) ([View Highlight](https://read.readwise.io/read/01kjdvaed58y137bgnk7t8xnnv))
	- Let Google Drive fully sync.
	  
	  Wait until sync is complete (green checkmark). ([View Highlight](https://read.readwise.io/read/01kjdvavgemxvx348129gpjegh))
	- On Laptop A:
	  
	  1.  Open Logseq
	    
	  2.  Choose:
	    
	    > Open → Select existing graph
	    
	  3.  Select:
	    
	    Code
	    
	    G:\My Drive\Logseq
	    
	  
	  Confirm everything works.
	  
	  If yes → Good. ([View Highlight](https://read.readwise.io/read/01kjdvfqf909cqb1y59jg7p5b0))
	- On Laptop B:
	  
	  •   Install Google Drive Desktop (Mirror mode)
	    
	  •   Wait for:
	    
	    Code
	    
	    G:\My Drive\Logseq
	    
	    to fully download ([View Highlight](https://read.readwise.io/read/01kjdvgnqtmq5ekny86kbd6pc4))
	- 1.  Open Logseq
	    
	  2.  Choose:
	    
	    > Open → Select existing graph
	    
	  3.  Select:
	    
	    Code
	    
	    G:\My Drive\Logseq
	    
	  
	  Now both laptops are pointing to the same mirrored folder. ([View Highlight](https://read.readwise.io/read/01kjdvhgfw4k4h4aqc3bgcvqmj))
	- Your graph root is:
	  
	  Code
	  
	  G:\MyDrive\logseqG\logseq
	  
	  NOT:
	  
	  Code
	  
	  G:\MyDrive\logseqG
	  
	  If inside `logseq` you see folders like:
	  
	  •   `journals`
	    
	  •   `pages`
	    
	  •   `logseq`
	    
	  •   `assets`
	    
	  
	  Then that is correct. ([View Highlight](https://read.readwise.io/read/01kjdvncz8pta63hw3n32yj083))
	- What To Do On Both Laptops
	  
	  On each laptop:
	  
	  1.  Open Logseq
	    
	  2.  Click **Open graph**
	    
	  3.  Select:
	    
	  
	  Code
	  
	  G:\MyDrive\logseqG\logseq ([View Highlight](https://read.readwise.io/read/01kjdvntvn3rd0ec2bfd40z5rf))