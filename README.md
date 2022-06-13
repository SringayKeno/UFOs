# UFOs

## Overview of the Analysis

Dana is a data journalist who is at a point in her career where she has the freedom to choose the topics she wants to write about. When she is given the opportunity to write about her hometownm, McMinnville Oregon, she jumps at the opportunity for a couple of reasons. First she gets to revisit her home town, and secondly it was the topic, Unidentified Flying Objects or (UFO)s. McMinnville is famous for its its UFO sightings and even has a annual gathering for UFO enthusiasts. 

Dana wants a simple html website that will contain her article on UFO's. Along with her article on the website, Dana wants to include a filterable table of all the sightings that she has access to in a javascript fill. The filterable findings will be used to support her article on the same website.


<img width="789" alt="Screenshot (131)" src="https://user-images.githubusercontent.com/102890151/173258645-dd538f65-589f-4a2a-ba85-afae11cd5be7.png">

The finished website (above). Sadly, there were no sightings in the javascript file for Dana's hometown of McMinnville Oregon.(below)

<img width="584" alt="Screenshot (132)" src="https://user-images.githubusercontent.com/102890151/173259217-f260dc54-81d4-40ef-b8ec-e73514afd40c.png">


## Results: There is a description of how to perform a search, with images. 

With user input the event listener detects changes to each of the filters (filters listed below). The function then saves the element, value and id of the filter and loops through the data and keeps any data that matches the filter values for the results of the search.

UFO sightings can be searched in five ways. Those Five ways are:

#### By Date

<img width="552" alt="date" src="https://user-images.githubusercontent.com/102890151/173258147-e7a29fa2-0bf5-4d6b-adbf-1582295b633b.png">

#### By City

<img width="555" alt="city" src="https://user-images.githubusercontent.com/102890151/173258140-f98fc0eb-7e8b-4178-8287-b249a1da8374.png">

#### By State

<img width="558" alt="Screenshot (121)" src="https://user-images.githubusercontent.com/102890151/173258117-8dbd429e-aa13-4184-b379-a090cab26d28.png">

#### By Country

<img width="563" alt="Screenshot (124)" src="https://user-images.githubusercontent.com/102890151/173257969-308bbd5b-0aef-4d53-a71d-2e37847c8c25.png">

#### By Shape of Sighting

<img width="570" alt="tri" src="https://user-images.githubusercontent.com/102890151/173257677-29778c16-fc6d-46b4-a818-6e299c7aec85.png">


## Summary:

### One drawback of this webpage 
One drawback of the website that is almost immediately apparent is the the site only only accepts lowercase input. For example, if one where to put 'CA' (California abbreviation) instead of 'ca' in the 'Enter State' field, no results would post. See images below.

Image on left with 'CA' in 'Enter State' field shows no results, while image on right with 'ca' input in same field yielded all results for California.

<img width="463" alt="Screenshot (108)" src="https://user-images.githubusercontent.com/102890151/173256084-a696643d-a4ac-4068-ba3c-74a2a8f67a10.png"> <img width="495" alt="Screenshot (107)" src="https://user-images.githubusercontent.com/102890151/173256082-17340f15-39ed-4da5-aee7-ade111fde38d.png">


### Two additional recommendations for further development

My first recommendation would be to add photos of sightings if any were avaiable for a particular sighting. If avaiable for a sighting I would create thumbnail of photo with the filtered results that could be clicked on. The website seems to need a photo, or something under the " UFO Sightings: Fact of Fancy? Ufologists Weigh In" banner. Perhaps when filter results are returned one of the photos for the filtered results could show there.

Second recommendation would be to accept capital letters misspellngs or alternate spellings to some degree in the fields for filtering. A few examples would are below in table.

<img width="370" alt="Screenshot (112)" src="https://user-images.githubusercontent.com/102890151/173256938-03a9a476-9ed8-4973-b122-aa4a0eb57005.png">



