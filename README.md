# Graduation-Project


>[!Caution]
> # WEB(ORGNIZER)

>[!warning]
> - LANDING PAGE

   - NAV BAR:
     - #HOME
     - #DARK_MODE_BUTTON
     - #SEARCH
     - #ABOUT will go down to about section
     - #services will go down to services section
     - #plan (future plan) or will create page that have our plans 
        - free
        - pro
     - #get_started
          - if not logged in will return to login page
          - if logged in (get_started) will disappear and photo of account appear and when click on it will appear three options (profile, Dashboard, settings, logout)
- ABOUT
- SERVICES
- PLANS ??!! 
- FOOTER
    - links,.............


>[!warning]
> - LOGIN PAGE

 - #email
 - #password
 - #reset_passowrd
 - #if_new_user_rigester_button
 - #login_with_google_and_facbook_microsoft.........

> AFTER LOGIN will redirect him to dashboard 


 >[!warning]
 > - get mobile app page


<img width="328" height="219" alt="Screenshot 2025-12-16 010628" src="https://github.com/user-attachments/assets/73f709e0-d1f7-4675-9ac4-454fc65eb2f0" />

> or some thing like that


>[!warning]
> - plans PAGE
>


<img width="260" height="221" alt="Screenshot 2025-12-16 012535" src="https://github.com/user-attachments/assets/e2c057c6-cc47-4872-af2f-df71e9d0ab8e" />

> this is future plan to our project we can not do it now 


>[!warning]
> - REGISTER PAGE

- #when user click on get_started it will open small window ask him login or register if login will redirect him to login page or window 
- if register will appear another window ask him if he 
    - normal user
        - will redirect him to get mobile app page 
    - orgnizer
        -  will redirect him to orgnizer register page
        - #registeration_component
            -  #organization_name * (it's priority field)
            - #Discriptions *
            - #logo *
            - #banner 
            - #offical_email *
            - #password *
            - #confirm_password *
            - #website
            - #address 
            - #category *  if not found in our list can add new one
            - #upload_company_papers * (السجل التجارى و المستندات القانونيه و البطاقه الضريبيه)
            - #check_box_of_polices *
                 
        - after finish register will redirect to confirmation email page and write code that will be sent on email
        - then will redirect to login







>[!warning]
> - Dashboard page
- DASHBOARD
 
    - #nav_bar
        - search
        - darkmode
        - notifications
        - language 
        - prfile_photo
            - name,email
            - profile
            - logout
    - #MAIN_PAGE  (ANALITECS,......)
        - state cards (static for now)
            - total events number
            - number of attendance people
            - average of actual attendance (qrcode)
            - rating average (التقيم اللى المستخدم هيقيمه بعد كل event)
        - latest 3-5 events
        - category analytics 
         - a مقارنه ربع سنويه لعدد الحضور 
    - #LIST_OF_EVENTS  +EDIT EVENT
        - state cards
            - total events
            - upcoming events
            - ended events
            - canceled events
        -  list of all events 
            - event name
            - event photo
            - event details summarized
            - event date
            - status  (active,......)
            - type (private, public)
            - category
            - name of creator 
            - number of attendance form total limit
            - average rating of event
            - button for edit
            - button for delete
                -  when click on event show all all all details
        - search 
        - export pdf to all events 
        - filters 
            - status (active, pending)
            - type (private, public)
            - advanced filter
                - filter by data
                - filter by attendance
                - filter by location
                - filter by category
                - filter by rating
                - filter by price (free , paid)
        - edit events
            -  same fields  + status (canceled)
    - #CREATE_EVENT choose_pay_checkbox(vip , normal,cstomize_prize)
        - main info
            - event name **
            - description **
            - Category **
            - status (active, pending) when pending  date info can't edited **
            - type of event (public or private)  **
                - if private generate invitation link  used for one time for limited time
            - event cover
        - date info
            -  starting date and ending date ** if ending date come change status to ended
            - starting time and ending time **
            - button for repetitive events 
        - location info **
            - physical
                - menu to suggested locations based on category
                - choose from map 
                - write location 
                    - Governorate
                    - Neighborhood/area
                    - street 
                    - building number
                    - final field appear the full location (non editable ) automatic based on his choose
            - online
                - link of event 
        - Tickets 
            - number of attendance 
                - unlimited 
                - specific number
            - paid
                - list of prepared tickets form tickets tab (VIP , normal, ........) can choose more than one for one event
                - customize ticket price
                    - price
                    - currency
            - free
        - choose team members from list that was prepared on team_members tab 
        - buttons to enable (chat , shared photos)
        - 
    - #INTERACTIONS_OF_EVENT POLLS , PHOTOS, ..... (frontend)
        - choose event from list of events each event (name, description , photo) 
            -  manage chat 
                - close chat  (admins only )
                - remove message 
                - pin message
                - admins have unique message preview 
            - manage photos
                - approve image form user before uploaded
            - Create vote 
                -  like WhatsApp 
            - view each event votes 
            - Create survey like (google forms) Future plan
                - view survey responses
    - #MANAGE_attendance  ALL FOLLOWERS , LIST OF EVENTS _(TO SEE each evet followers)_ + view user or block user
        - list of all followers (names, emails)
            - block follower 
        - list of events 
            - each event attendance 
                - name 
                - email
                - RSVP status
                - attendance time
                - his rate 
        - filter
            - RSVP
            - NAME
            - attendance time 
            - rate
        - send email to all 
    - #Team_members 
        - cards describe each role   
        - add team member
            -  name
            - email
            - choose role (owner, admin, moderator)
                - owner : have all privileges
                - admin :  later.....
                - moderator : later .......
                - scan-user : only scan tickets  
            - photo
        - delete team member 
        - edit team member
        - search
    - #Tickets_finance_analitycs (create tickets types)
        - will contain three tabs :
        - analytics 
            -  finance cards analytics 
            - best 5 events
            - finance analytics
            -  analytics to private and public events
            - actual attendance vs people who click will attend but not attend
        - Generate Ticket
            - select type (VIP, Golden,  normal,....)
            - choose price
            - edit ticket 
            - delete ticket
        - finance gate settings (future plan)
            - PayPal 
            - master card
            - Meza
            - etc., .......... 
    - #support_team (not complete)
        -  chat for each user to contact our support team
    - #notifications 
        - if user buy ticket 
        - if number of users is completed for event 
        - if event stated and ended
        - if user upload photos and wait for approve 
    - #settings (orginzition_profile_settings, change pass, .....) + use plan of website free or pro
        - profile settings
            - change name
            - change password
            - change logo
            - change cover
            - change email
            - change discerption
            - change website
            - change address 
        - my plan
            - choose plan 


>[!Caution]
> # admin_Dashboard

- manage organization 
    - list of organizations  
    - organization details
        - approve 
        - deny
    - Delete organization
- manage users
    - List of users
    - Block or delete user
- add Apis to get events different sources 





## **`analytics photos`**



- actual attenctance vs people who click will attend but not attend

<img width="738" height="588" alt="Screenshot 2025-12-16 020648" src="https://github.com/user-attachments/assets/915138ff-98dd-41a7-9e9d-8312af07eaaa" />


- analytics to private and public events

<img width="291" height="339" alt="Screenshot 2025-12-16 021038" src="https://github.com/user-attachments/assets/d434fc0f-2237-4d5f-bc9a-ff2caa4cfa59" />


- finance analytics

<img width="1427" height="796" alt="Screenshot 2025-12-16 021343" src="https://github.com/user-attachments/assets/261c24ab-cd75-46b0-8e5c-022ef014493d" />


- finance cards analytics


<img width="1554" height="420" alt="Screenshot 2025-12-16 021432" src="https://github.com/user-attachments/assets/a3afaa68-2a8a-4e64-a6f8-7e0568115651" />



- category analytics  (Done)

<img width="488" height="557" alt="Screenshot 2025-12-16 021532" src="https://github.com/user-attachments/assets/7329f961-1619-4c30-81e1-85520ea6ce32" />


- best 5 events 

<img width="1539" height="634" alt="Screenshot 2025-12-16 022028" src="https://github.com/user-attachments/assets/fc51f1f1-8b0e-41a0-9a37-3d4cb9763baf" />





- مقارنه ربع سنويه لعدد الحضور  (done)


<img width="872" height="597" alt="image" src="https://github.com/user-attachments/assets/59dcff07-135a-4729-a5b6-b9f25f12af8d" />

















































































































