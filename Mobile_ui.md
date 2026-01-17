
>[!Caution] 
> mobile (User)


>[!warning]
> login page

- #email 
- #password 
- #Forget_password_link
- #login_with_google_and_facbook_microsoft.........


>[!warning]
> Rigster

- #name
- #photo
- #email
- #password 
- #confirm_password
- #interested_events_type
- #bio
- #location (fields of options {city, region, address text} )  or use current location.   


>[!warning]
> Profile

- #name
- #photo
- #email
- #change_password_button (on click will show popup box for change password)
     - #first_popup
	- old password (with send otp button to email)
	- #second_popup
    - check otp
    - #third_popup
    - new password
    - confirm new password
    - submit button 
- #interested_events_type 
    - edit interested or add interested 
- #bio
- #location 
- #Delete_account_button (popup to take password)




>[!warning]
> main page


- #bottom_nav_bar

<img width="425" height="81" alt="Screenshot 2026-01-17 183021" src="https://github.com/user-attachments/assets/e3b83a08-ebb8-4afb-88ec-be841cb3cc0d" />


- main page
- events
-  floating button (add meetup)

<img width="1704" height="531" alt="Screenshot 2026-01-17 184424" src="https://github.com/user-attachments/assets/46a3237e-13ea-4089-82ab-77aeb82ffc92" />


- Community (meetups that user will create)
- more (refer to side menu page)
    - side menu :
        - main page 
        - events
        - Community 
        - organizations 
         ------------------------------ 
        - tickets (my tickets for events that i will attend)
        - favorites 
        - Followed organizations 
        - my meetups
         -------------------------------
         - language (switch button)
         - terms & conditions
         - privacy 
         - contact with us
         -------------------------------
         - logout button


- #app_bar
    - user photo 
    - welcome + name
    - notification 



<img width="432" height="91" alt="Screenshot 2026-01-17 183034" src="https://github.com/user-attachments/assets/1d65fefa-5d43-45f6-8cd5-7727f3e5b266" />



- #hero_section  
    - slider to show best 5 events 




- #horizontal_section for events around you + meetups


<img width="588" height="571" alt="Screenshot 2026-01-17 174810" src="https://github.com/user-attachments/assets/07765fd8-24fb-4505-9d7d-e2d5e7009227" />


## Two tabs (toggle button)

- events around you  (First tab)
    - each card :
        - photo
        - Title
        - location
        - time
        - number of attendance 
        - favorite icon

- (commuinity_meetups) (second tab)
     - each card (another style to card not like events around you) :
        - photo
        - Title
        - location
        - time
        - number of attendance 



<img width="600" height="731" alt="Screenshot 2026-01-17 194036" src="https://github.com/user-attachments/assets/d388b3a7-d044-4ee8-96ac-695cad1a25db" />




- #horizontal_list for organizations 


<img width="468" height="146" alt="Screenshot 2026-01-17 193301" src="https://github.com/user-attachments/assets/c70d43a4-c079-4a84-857e-948f444916b9" />

Note (for clarifications)  : السطر هيشيل تلاته بس كبرى الحجم لحد ما السطر ياخد 3



- #horizontal_section for user preferences 
    - each card (another style to card not like events around you) :
        - photo
        - Title
        - location
        - time
        - number of attendance 
        - favorite icon




- #vertical_sectoin followed organizations events
    - each card (another style) :
        - photo
        - Title
        - location
        - time
        - number of attendance 
        - favorite icon



>[!warning]
> events


- #search + filter icon 
    - filter icon will open modal with filtration options  
        - time
        - city 
        - region
        - category 
        - sort by 
            - oldest
            - newest
            - biggest traffic 
        - switch button ( free only )
        - submit button
- #LIST_OF_EVENTS ( vertical )

>[!Caution]
> note
> copy vertical card component in home page



>[!warning]
> Community (meetups)


- #search + filter icon 
    - filter icon will open modal with filtration options  
        - time
        - city 
        - region
        - category 
        - sort by 
            - oldest
            - newest
            - biggest traffic 
        - submit button


- #Grid_list_of_meetups

>[!Caution]
> note
> use the same component of meetups in home page

 > ##  when click on meetup display meetup detail page


- photo
- title
- date
- time
- location
    - offline 
        -  physical location 
        - map
    - online
        - link of event
- category
- description
- max number of attendance
- status
    - upcoming
    - ended
- rating when meetup ended
- rating button
- end meetup button ( showing if the user is owner )
- owner list tile :
    - photo
    - name
- button for attend or not 




>[!warning]
> Tickets (events will attend)



- #search + filter icon 
    - filter icon will open modal with filtration options  
        - status
            - ended (finished) 
            - upcoming 
        - sort by 
            - oldest
            - newest
        - toggle button 
            - free
            - paid
        - submit button


- #vertical_list_of_Ticket_of_events

- each ticket
    - Title 
    - location
    - date
    - ticket number
    - ticket status
        - pending
        - upcoming
    - free or paid



>[!warning]
> orgnizations



- #search + filter icon 
    - filter icon will open modal with filtration options  
        - city 
        - region
        - category
        - sort by 
            - oldest
            - newest
            - biggest traffic 
        - submit button


- #GRID_LIST_OF_ORGNIZATIONS

- each card has:
    - name
    - category
    - photo
    - city
    - followers
    - events number
    - follow button request





>[!warning]
> favorites


- #LIST_OF_EVENTS ( vertical )

>[!Caution]
> note
> - in home page we have two cards design 
> - in events list page we told you to use the same card of home so you now already used one so use the other one  
    






>[!warning]
> Followed organizations 


- #search 
- #vertical_list_of_orgnization
    - each item is small list tile that display just :
        - photo
        - name 
        - subscription date





>[!warning]
> my meetups


- #search + filter icon 
    - filter icon will open modal with filtration options  
        - time
        - category 
        - sort by 
            - oldest
            - newest
            - biggest traffic 
        - submit button


- #Grid_list_of_meetups

>[!Caution]
> note
> use the same component of meetups in home page






>[!warning]
> when click on floating button (add meetup)


add :

- photo
- title
- date
- time
- location
    - offline 
        - manually
            - street 
            - region dropdown list
            - city dropdown list
        - choose form map 
    - online
        - put link for meetup  
- category
- description
- max number of attendance



>[!warning]
> event page details


- cover
- title
- date
- time
- location
    - offline 
        -  physical location 
        - map
    - online
        - link of event
- category
- description
- free or paid
- max number of attendance
- status
    - upcoming
    - ended
- rating when meetup ended
- rating button
- organization
- button for attend or not 
- tabs:   ********************************************************* ************* *********     * ** * * * * * * **  * * *  * * * * * * ** * * *  ** * * * *
     - discussion board
     - polls
     - feedback form 
     - media (photos, videos)



>[!warning]
> orgnizer page


- photo 
- cover
- name
- description
- category
- team members 
- number of followers
- location
    - map
    - physical location
- website
- email
- contact button
    - will display chat page with organizer  
- follow button



- #events_tab_bar
    - two tabs :
        - one for upcoming events 
        - one for ended events
    - will display tab view for each of them




>[!warning]
> notification page


will display vertical list of notifications 


------------------









> [!danger] not complete
> - ## settings
> - ## tabs on event page













