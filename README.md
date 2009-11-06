Scraper 
=======

A single uri image scraper.

Usage
-----
    
    scraper <source> <destination>
    
e.g.

    scraper http://www.boston.com/bigpicture/2009/10/china_as_seen_by_elizabeth_dal.html ~/Desktop
    
Notes
-----
    
- The images downloaded will be saved to a directory with the name of the source, in a sluggified form. e.g. in the case of the example above, the images will be saved to:

        ~/Desktop/http-www-boston-com-bigpicture-2009-10-china_as_seen_by_elizabeth_dal-html/

- Small images (below 20Kb) will be discarded.    

- The images downloaded are saved with their original filenames, with a random-ish number prefix. This is to allow multiple batches to be dumped into a single directory without name clashes, e.g.

        18283__pretty_picture.jpg

- This script is pleased to require Hpricot (`gem install hpricot`)

License
-------
Do what you want.



  