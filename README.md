Georgia


This is one out of many scripts in a Democracy Works contract to help voters get to the polls. The data I scraped and parsed was passed to Google Maps. Before this project there was no national public database of early polling hours, locations, and voting official phone numbers. That information -- for thousands of jurisdictions in the country -- was only, at best, to be found on state government websites, organized by county. The state government websites are all formatted differently. I scraped each state website different, using Mechanize to click through the links and Nokogiri to find the right data based on css selectors. I used the Ruby CSV gem to put it in a spreadsheet to send to Google. 
