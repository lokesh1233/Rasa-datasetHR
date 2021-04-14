## email support
* email_support
    - action_email_support
    - action_restart

## feedback options
* feedback
    - utter_feedback
    - action_restart

## feedback options
* feedback{"confirm": "cancel"}
  - slot{"confirm":"cancel"}
    - utter_feedback
    - action_restart

## it_vpnloginissue 1
* it_vpnloginissue
    - utter_it_vpnloginissue1
* confirm
    - utter_it_vpnloginissue6
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_vpnloginissue 2
* it_vpnloginissue
    - utter_it_vpnloginissue1
* confirm
    - utter_it_vpnloginissue6
* deny
    - utter_it_vpnloginissue2
* confirm
    - utter_it_vpnloginissue4
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_vpnloginissue 2a
* it_vpnloginissue
    - utter_it_vpnloginissue1
* confirm
    - utter_it_vpnloginissue6
* deny
    - utter_it_vpnloginissue2
* deny
    - utter_it_vpnloginissue3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_vpnloginissue 3
* it_vpnloginissue
    - utter_it_vpnloginissue1
* deny
    - utter_it_vpnloginissue5
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_vpnloginissue 4
* it_vpnloginissue
    - utter_it_vpnloginissue1
* deny
    - utter_it_vpnloginissue5
* deny
    - utter_it_vpnloginissue6
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_vpnloginissue 5
* it_vpnloginissue
    - utter_it_vpnloginissue1
* deny
    - utter_it_vpnloginissue5
* deny
    - utter_it_vpnloginissue6
* deny
    - utter_it_vpnloginissue2
* deny
    - utter_it_vpnloginissue3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_o360loginissue
* it_o360loginissue
    - utter_it_o360loginissue
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_passwordreset
* it_passwordreset
    - utter_it_passwordreset
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting
* it_wifinotconnecting
    - utter_it_wifinotconnecting1
    - action_restart

## it_wifinotconnecting1
* it_wificonnectionissue
    - utter_it_vpnloginissue1
* confirm
    - utter_it_wifinotconnecting2
* confirm
    - utter_it_wifinotconnecting3
* deny
    - utter_it_wifinotconnecting1a
* confirm
    - utter_it_lan_cable_no_internet5
* deny
    - utter_it_printernotworking6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting1a
* it_wificonnectionissue
    - utter_it_vpnloginissue1
* confirm
    - utter_it_wifinotconnecting2
* confirm
    - utter_it_wifinotconnecting3
* deny
    - utter_it_wifinotconnecting1a
* deny
    - utter_it_printernotworking6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting1b
* it_wificonnectionissue
    - utter_it_vpnloginissue1
* confirm
    - utter_it_wifinotconnecting2
* confirm
    - utter_it_wifinotconnecting3
* deny
    - utter_it_wifinotconnecting1a
* confirm
    - utter_it_lan_cable_no_internet5
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting2
* it_wificonnectionissue
    - utter_it_vpnloginissue1
* confirm
    - utter_it_wifinotconnecting2
* confirm
    - utter_it_wifinotconnecting3
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting3
* it_wificonnectionissue
    - utter_it_vpnloginissue1
* confirm
    - utter_it_wifinotconnecting2
* deny
    - utter_it_ftpaccessissue3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting4
* it_wificonnectionissue
    - utter_it_vpnloginissue1
* deny
    - utter_it_vpnloginissue5
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting5
* it_wificonnectionissue
    - utter_it_vpnloginissue1
* deny
    - utter_it_vpnloginissue5
* deny
    - utter_it_wifinotconnecting2
* confirm
    - utter_it_wifinotconnecting3
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting6
* it_wificonnectionissue
    - utter_it_vpnloginissue1
* deny
    - utter_it_vpnloginissue5
* deny
    - utter_it_wifinotconnecting2
* deny
    - utter_it_ftpaccessissue3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting7
* it_wifiinternetissue
    - utter_it_wifinotconnecting3
* deny
    - utter_it_wifinotconnecting1a
* confirm
    - utter_it_lan_cable_no_internet5
* deny
    - utter_it_printernotworking6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting7a
* it_wifiinternetissue
    - utter_it_wifinotconnecting3
* deny
    - utter_it_wifinotconnecting1a
* deny
    - utter_it_printernotworking6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting7b
* it_wifiinternetissue
    - utter_it_wifinotconnecting3
* deny
    - utter_it_wifinotconnecting1a
* confirm
    - utter_it_lan_cable_no_internet5
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_wifinotconnecting8
* it_wifiinternetissue
    - utter_it_wifinotconnecting3
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_windows10builtinappsnotworking
* it_windows10builtinappsnotworking
    - utter_it_windows10builtinappsnotworking
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_systemaudionotworking
* it_systemaudionotworking
    - utter_it_systemaudionotworking
    - utter_like_dislike
    - action_restart

## it_systemhangissue
* it_systemhangissue
    - utter_it_systemhangissue
    - utter_like_dislike
    - action_restart

## it_printernotworking1
* it_printernotworking
    - utter_it_printernotworking9
* confirm
    - utter_it_printernotworking14
* it_no_paper
    - utter_it_printernotworking13
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking2
* it_printernotworking
    - utter_it_printernotworking9
* confirm
    - utter_it_printernotworking14
* it_paper_jam
    - utter_it_printernotworking12
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking3
* it_printernotworking
    - utter_it_printernotworking9
* confirm
    - utter_it_printernotworking14
* it_printer_catridge_empty
    - utter_it_printernotworking11
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking4
* it_printernotworking
    - utter_it_printernotworking9
* confirm
    - utter_it_printernotworking14
* it_printer_offline
    - utter_it_printernotworking2
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_printernotworking5
* it_printernotworking
    - utter_it_printernotworking9
* confirm
    - utter_it_printernotworking14
* it_printer_offline
    - utter_it_printernotworking2
* deny
    - utter_it_printernotworking10
* confirm
    - utter_it_printernotworking5
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking6
* it_printernotworking
    - utter_it_printernotworking9
* confirm
    - utter_it_printernotworking14
* it_printer_offline
    - utter_it_printernotworking2
* deny
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* confirm
    - utter_it_printernotworking4
* confirm
    - utter_it_printernotworking5
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking7
* it_printernotworking
    - utter_it_printernotworking9
* confirm
    - utter_it_printernotworking14
* it_printer_offline
    - utter_it_printernotworking2
* deny
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* deny
    - utter_it_printernotworking8
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking8
* it_printernotworking
    - utter_it_printernotworking9
* confirm
    - utter_it_printernotworking14
* it_printer_offline
    - utter_it_printernotworking2
* deny
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* confirm
    - utter_it_printernotworking4
* deny
    - utter_it_printernotworking7
* deny
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_printernotworking9
* it_printernotworking
    - utter_it_printernotworking9
* confirm
    - utter_it_printernotworking14
* it_printer_offline
    - utter_it_printernotworking2
* deny
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* confirm
    - utter_it_printernotworking4
* deny
    - utter_it_printernotworking7
* confirm
    - utter_it_printernotworking6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking10
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* deny
    - utter_it_printernotworking2
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_printernotworking11
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* deny
    - utter_it_printernotworking2
* deny
    - utter_it_printernotworking10
* confirm
    - utter_it_printernotworking5
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking12
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* deny
    - utter_it_printernotworking2
* deny
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* confirm
    - utter_it_printernotworking4
* confirm
    - utter_it_printernotworking5
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking13
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* deny
    - utter_it_printernotworking2
* deny
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* deny
    - utter_it_printernotworking8
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking14
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* deny
    - utter_it_printernotworking2
* deny
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* confirm
    - utter_it_printernotworking4
* deny
    - utter_it_printernotworking7
* deny
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_printernotworking15
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* deny
    - utter_it_printernotworking2
* deny
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* confirm
    - utter_it_printernotworking4
* deny
    - utter_it_printernotworking7
* confirm
    - utter_it_printernotworking6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking16
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* confirm
    - utter_it_printernotworking10
* confirm
    - utter_it_printernotworking5
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking17
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* confirm
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* confirm
    - utter_it_printernotworking4
* confirm
    - utter_it_printernotworking5
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking18
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* confirm
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* deny
    - utter_it_printernotworking8
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_printernotworking19
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* confirm
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* confirm
    - utter_it_printernotworking4
* deny
    - utter_it_printernotworking7
* deny
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_printernotworking20
* it_printernotworking
    - utter_it_printernotworking9
* deny
    - utter_it_printernotworking1
* confirm
    - utter_it_printernotworking10
* deny
    - utter_it_printernotworking3
* confirm
    - utter_it_printernotworking4
* deny
    - utter_it_printernotworking7
* confirm
    - utter_it_printernotworking6
    - action_it_ticket_update
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_ftpaccessissue
* it_ftpaccessissue
    - utter_it_ftpaccessissue1
    - action_restart

## it_ftpaccessissue1
* it_ftploginissue
    - utter_it_vpnloginissue1
* confirm
    - utter_it_ftpaccessissue2
* confirm
    - utter_it_ftpaccessissue4
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_ftpaccessissue2
* it_ftploginissue
    - utter_it_vpnloginissue1
* confirm
    - utter_it_ftpaccessissue2
* deny
    - utter_it_ftpaccessissue3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_ftpaccessissue3
* it_ftploginissue
    - utter_it_vpnloginissue1
* deny
    - utter_it_vpnloginissue5
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_ftpaccessissue4
* it_ftploginissue
    - utter_it_vpnloginissue1
* deny
    - utter_it_vpnloginissue5
* deny
    - utter_it_ftpaccessissue2
* deny
    - utter_it_ftpaccessissue3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_ftpaccessissue5
* it_ftploginissue
    - utter_it_vpnloginissue1
* deny
    - utter_it_vpnloginissue5
* deny
    - utter_it_ftpaccessissue2
* confirm
    - utter_it_ftpaccessissue4
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_ftpaccessissue6
* it_ftpconnectionissue
    - utter_it_printernotworking4
* confirm
    - utter_it_ftpaccessissue4
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_ftpaccessissue7
* it_ftpconnectionissue
    - utter_it_printernotworking4
* deny
    - utter_it_printernotworking7
* confirm
    - utter_it_printernotworking6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_ftpaccessissue8
* it_ftpconnectionissue
    - utter_it_printernotworking4
* deny
    - utter_it_printernotworking7
* deny
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_msteamsnotworking
* it_msteamsnotworking
    - utter_it_msteamsnotworking
    - utter_like_dislike
    - action_restart

## it_needtosetoutofofficeinoutlook
* it_needtosetoutofofficeinoutlook
    - utter_it_needtosetoutofofficeinoutlook
    - utter_like_dislike
    - action_restart

## it_keyboardmouseissues
* it_keyboardmouseissues
    - utter_it_keyboardmouseissues
    - utter_like_dislike
    - action_restart

## End the conversation
* conversationEnd
    - utter_conversationEnd
    - action_restart

## it help desk faqs
* it_helpdesk_FAQs
    - utter_it_helpdesk_FAQs
    - action_restart

## Corona

* Events 
    - action_events
    - utter_like_dislike
    - action_restart

## goodafternoon

* goodafternoon 
    - utter_goodafternoon
    - action_restart

## Corona

* Corona 
    - action_coronaDetails
    - utter_like_dislike
    - action_restart

## covid 19 flow

* Covid19
    - utter_Covid19
    - action_restart

## covid 19 help line flow

* CovidHelpline
    - utter_CovidHelpline
    - utter_like_dislike
    - action_restart

##Awareness

* Awareness
    - utter_Awareness
    - utter_like_dislike
    - action_restart

## policy learning

* policyLearning
   - utter_policyLearning
   - utter_like_dislike
   - action_restart

## policy Benefits

* policyBenefits
   - utter_policyBenefits
   - utter_like_dislike
   - action_restart

## absolutely not

* absolutely_not
   - utter_absolutely_not
   - action_restart

## excellent

* excellent
   - utter_excellent
   - action_restart

## could help

* could_help
   - utter_could_help
   - action_restart

## hear it

* hear_it
   - utter_hear_it
   - action_restart

## goodevening

* goodevening
   - utter_goodevening
   - action_restart

## goodmorning

* goodmorning
   - utter_goodmorning
   - action_restart

## goodnight

* goodnight
   - utter_goodnight
   - action_restart

## goodbye

* goodbye OR goodbye{"DATE":"tomorrow"}
   - utter_goodbye
   - action_restart

## hello there

* hello_there 
  - utter_hello_there
  - action_restart

## hello

* hello
   - utter_hello
   - action_restart

## couldnot say

* couldnot_say
   - utter_couldnot_say
   - action_restart

## things wrong

* things_wrong
   - utter_things_wrong
   - action_restart

## working on

* working_on
   - utter_working_on
   - action_restart

## no name

* no_name
   - utter_no_name
   - action_restart

## trust judgment

* trust_judgment
   - utter_trust_judgment
   - action_restart

## bot help

* bot_help
   - utter_bot_help
   - action_restart

## upset

* upset
   - utter_upset
   - action_restart

## help answers

* help_answers
   - utter_help_answers
   - action_restart

## not sure

* not_sure
   - utter_not_sure
   - action_restart

## sorry chat

* sorry_chat
   - utter_sorry_chat
   - action_restart

## sorry

* sorry
   - utter_sorry
   - action_restart

## wish

* wish
   - utter_wish
   - action_restart

## anything later

* anything_later
   - utter_anything_later
   - action_restart

## apologies

* apologies
   - utter_apologies
   - action_restart

## no problem

* no_problem
   - utter_no_problem
   - action_restart

## of course

* of_course
   - utter_of_course
   - action_restart

## oh dear

* oh_dear
   - utter_oh_dear
   - action_restart

## okay got

* okay_got
   - utter_okay_got
   - action_restart

## okay

* okay
   - utter_okay
   - action_restart

## opposite

* opposite
   - utter_opposite
   - utter_like_dislike
   - action_restart

## sorry lost

* sorry_lost
   - utter_sorry_lost
   - utter_like_dislike
   - action_restart

## question

* question
   - utter_question
   - action_restart

## take time

* take_time
   - utter_take_time
   - action_restart

## thankyou day

* thankyou_day
   - utter_thankyou_day
   - utter_like_dislike
   - action_restart

## thankyou kind

* thankyou_kind
   - utter_thankyou_kind
   - utter_like_dislike
   - action_restart

## thank you

* thank_you
   - utter_thank_you
   - utter_like_dislike
   - action_restart

## simple wonderful

* simple_wonderful
   - utter_simple_wonderful
   - utter_like_dislike
   - action_restart

## nothing

* nothing
   - utter_nothing
   - utter_like_dislike
   - action_restart

## wonderful

* wonderful
   - utter_wonderful
   - utter_like_dislike
   - action_restart

## balance leaves

* leaveBalance
    - action_leave_balance
    - utter_like_dislike
    - action_restart

## leave FAQ1

* leaveTakes
  - action_leaveTakes
  - utter_like_dislike
  - action_restart

## leave miscarriage

* leaveMisCarriage
  - utter_leaveMisCarriage
  - utter_like_dislike
  - action_restart

## leave eligibility

* leaveEligibility
  - action_leaveEligibility
  - utter_like_dislike
  - action_restart

## leave eligibility

* leaveEligibility{"leaveType":"birthday"}
  - slot{"leaveType":"birthday"}
  - action_leaveEligibility
  - utter_like_dislike
  - action_restart

## leave status

* leaveStatus
  - action_leaveStatus
  - utter_like_dislike
  - action_restart

## leave status list

* leaveStatus{"leaveType":"birthday"}
  - slot{"leaveType":"birthday"}
  - action_leaveStatus
  - utter_like_dislike
  - action_restart

## leave type days

* leaveTypeDays
  - action_leaveTypeDays
  - utter_like_dislike
  - action_restart

## leave type days

* leaveTypeDays{"leaveType":"birthday"}
  - slot{"leaveType":"birthday"}
  - action_leaveTypeDays
  - utter_like_dislike
  - action_restart

## leave notification

* leaveNotification
  - utter_leaveNotification
  - utter_like_dislike
  - action_restart

## New Story

* leaveTakes{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - action_leaveTakes
    - utter_like_dislike
    - action_restart

## New Story

* leaveCheckPMO{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveCheckPMO
    - utter_like_dislike
    - action_restart
* leaveCheckPMO{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveCheckPMO
    - utter_like_dislike
    - action_restart
* leaveCheckPMO{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveCheckPMO
    - utter_like_dislike
    - action_restart

## New Story

* leaveAvailMonth{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveAvailMonth
    - utter_like_dislike
    - action_restart
* leaveAvailMonth{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveAvailMonth
    - utter_like_dislike
    - action_restart
* leaveAvailMonth{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveAvailMonth
    - utter_like_dislike
    - action_restart

## New Story

* leaveAvailAnnual{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveAvailAnnual
    - utter_like_dislike
    - action_restart
* leaveAvailAnnual{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveAvailAnnual
    - utter_like_dislike
    - action_restart
* leaveAvailAnnual{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveAvailAnnual
    - utter_like_dislike
    - action_restart

## New Story

* leaveOurPolicy{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveOurPolicy
    - utter_like_dislike
    - action_restart
* leaveOurPolicy{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveOurPolicy
    - utter_like_dislike
    - action_restart
* leaveOurPolicy{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveOurPolicy
    - utter_like_dislike
    - action_restart

## New Story

* leaveMedical{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveMedical
    - utter_like_dislike
    - action_restart
* leaveMedical{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveMedical
    - utter_like_dislike
    - action_restart
* leaveMedical{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveMedical
    - utter_like_dislike
    - action_restart

## New Story

* leaveClsCarry{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveClsCarry
    - utter_like_dislike
    - action_restart
* leaveClsCarry{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveClsCarry
    - utter_like_dislike
    - action_restart
* leaveClsCarry{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveClsCarry
    - utter_like_dislike
    - action_restart

## New Story

* leaveValidCompoff{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveValidCompoff
    - utter_like_dislike
    - action_restart
* leaveValidCompoff{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveValidCompoff
    - utter_like_dislike
    - action_restart
* leaveValidCompoff{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveValidCompoff
    - utter_like_dislike
    - action_restart

## New Story

* leaveLogTime{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveLogTime
    - utter_like_dislike
    - action_restart
* leaveLogTime{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveLogTime
    - utter_like_dislike
    - action_restart
* leaveLogTime{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveLogTime
    - utter_like_dislike
    - action_restart

## New Story

* leaveCarryForwarded{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveCarryForwarded
    - utter_like_dislike
    - action_restart
* leaveCarryForwarded{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveCarryForwarded
    - utter_like_dislike
    - action_restart
* leaveCarryForwarded{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveCarryForwarded
    - utter_like_dislike
    - action_restart

## New Story

* leaveYesQuery{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveYesQuery
    - utter_like_dislike
    - action_restart
* leaveYesQuery{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveYesQuery
    - utter_like_dislike
    - action_restart
* leaveYesQuery{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveYesQuery
    - utter_like_dislike
    - action_restart

## New Story

* leaveAutoApproved{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveAutoApproved
    - utter_like_dislike
    - action_restart
* leaveAutoApproved{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveAutoApproved
    - utter_like_dislike
    - action_restart
* leaveAutoApproved{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveAutoApproved
    - utter_like_dislike
    - action_restart

## New Story

* leaveFH{"leaveType":"birthday","DATE":"year"}
    - slot{"DATE":"year"}
    - slot{"leaveType":"birthday"}
    - utter_leaveFH
    - utter_like_dislike
    - action_restart
* leaveFH{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveFH
    - utter_like_dislike
    - action_restart
* leaveFH{"DATE":"year"}
    - slot{"DATE":"year"}
    - utter_leaveFH
    - utter_like_dislike
    - action_restart

## leave auto approved

* leaveAutoApproved
  - utter_leaveAutoApproved
  - utter_like_dislike
  - action_restart

## leave FAQ14

* leaveFH
  - utter_leaveFH
  - utter_like_dislike
  - action_restart

## leave FAQ2

* leaveCheckPMO
  - utter_leaveCheckPMO
  - utter_like_dislike
  - action_restart

## leave FAQ3

* leaveAvailMonth
  - utter_leaveAvailMonth
  - utter_like_dislike
  - action_restart

## leave FAQ4

* leaveAvailAnnual
  - utter_leaveAvailAnnual
  - utter_like_dislike
  - action_restart

## leave FAQ5

* leaveOurPolicy
  - utter_leaveOurPolicy
  - utter_like_dislike
  - action_restart

## leave policy

* policyLeave
  - utter_policy
  - utter_like_dislike
  - action_restart

## status leave

* leaveStatus OR leaveStatus{"period":"current"}
  - action_leaveStatus
  - utter_like_dislike
  - action_restart

## Help Leave

* help_leave
  - utter_helpLeave
  - action_restart

## Help EWC

* help_EWC
  - utter_helpEWC
  - action_restart

## Help EWC

* help_EWC{"leaveType":"WFH"}
  - slot{"leaveType":"WFH"}
  - utter_helpEWC
  - action_restart

## balance leaves with type

* leaveBalance OR leaveBalance{"leaveType":"sick"}
  - slot{"leaveType":"sick"}
  - action_leave_balance
  - utter_like_dislike
  - action_restart

## holiday

* holiday{"DATE":"tomorrow", "time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"tomorrow"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"time":"2019-09-28T00:00:00.000-07:00"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart

## date

* date{"DATE":"12 - 10 - 2019"}
    - slot{"DATE":"12 - 10 - 2019"}
    - utter_dateVal
    - utter_like_dislike
    - action_restart

## leave FAQ6

* leaveMedical
     - utter_leaveMedical
     - utter_like_dislike
     - action_restart

## leave FAQ7

* leaveClsCarry
     - utter_leaveClsCarry
     - utter_like_dislike
     - action_restart

## leave FAQ8

* leaveValidCompoff
     - utter_leaveValidCompoff
     - utter_like_dislike
     - action_restart

## leave FAQ9

* leaveLogTime
     - utter_leaveLogTime
     - utter_like_dislike
     - action_restart

## leave FAQ10

* leaveCarryForwarded
     - utter_leaveCarryForwarded
     - utter_like_dislike
     - action_restart

## leave FAQ11

* leaveYesQuery
     - utter_leaveYesQuery
     - utter_like_dislike
     - action_restart

## Chat with me

* holiday{"DATE":"tomorrow"}
    - slot{"DATE":"tomorrow"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* leaveStatus
    - action_leaveStatus
    - utter_like_dislike
    - action_restart

## Chat with me

* holiday{"DATE":"tomorrow"} OR holiday{"period":"next"}
    - slot{"DATE":"tomorrow"}
    - slot{"period":"next"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* leaveStatus
    - action_leaveStatus
    - utter_like_dislike
    - action_restart
* leaveStatus
    - action_leaveStatus
    - utter_like_dislike
    - action_restart
* holiday{"DATE":"tomorrow"} OR holiday{"period":"next"}
    - slot{"DATE":"tomorrow"}
    - slot{"period":"next"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"time":"2019-09-28T00:00:00.000-07:00"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* bot_help
    - utter_bot_help
    - utter_like_dislike
    - action_restart

## Chat with me

* leaveStatus
    - action_leaveStatus
    - utter_like_dislike
    - action_restart
* leaveStatus
    - action_leaveStatus
    - utter_like_dislike
    - action_restart
* leaveLogTime
    - utter_leaveLogTime
    - utter_like_dislike
    - action_restart

## Chat with me

* holiday{"DATE":"tomorrow"}
    - slot{"DATE":"tomorrow"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"DATE":"next week"}
    - slot{"DATE":"next week"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"DATE":"07 - 09 - 2019"}
    - slot{"DATE":"07 - 09 - 2019"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"DATE":"next monday"}
    - slot{"DATE":"next monday"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* date{"DATE":"12 - 10 - 2019"}
    - slot{"DATE":"12 - 10 - 2019"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart

## holiday with no date

* holiday
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* date{"DATE":"12-10-2019"}
    - slot{"DATE":"12-10-2019"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart

## Chat with me

* holiday
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* date{"DATE":"12 - 10 - 2019"}
    - slot{"DATE":"12 - 10 - 2019"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart

## Chat with me

* holiday
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* date{"DATE":"12 - 10 - 2019"}
    - slot{"DATE":"12 - 10 - 2019"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* date{"DATE":"12 - 20 - 2019"}
    - slot{"DATE":"12 - 20 - 2019"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart

## Chat with me

* date{"DATE":"12 - 20 - 2019"}
    - slot{"DATE":"12 - 20 - 2019"}
    - utter_dateVal
    - utter_like_dislike
    - action_restart

## Chat with me

* holiday{"DATE":"tomorrow"}
    - slot{"DATE":"tomorrow"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"period":"next", "time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"period":"next"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* date{"DATE":"22 - 23 - 2019", "time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"22 - 23 - 2019"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"DATE":"23 - 10 - 2019"}
    - slot{"DATE":"23 - 10 - 2019"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart

## help cancel

* help_cancel
    - utter_helpcancel
    - utter_like_dislike
    - action_restart

## Chat with me

* leaveBalance{"period":"current"}
    - slot{"leaveType":"birthday"}
    - action_leave_balance
    - utter_like_dislike
    - action_restart

## null story

* null
    - utter_bullShit
    - utter_like_dislike
    - action_restart

## Chat with me

* holiday{"period":"previous"}
    - slot{"period":"previous"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"period":"next"}
    - slot{"period":"next"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"period":"next"}
    - slot{"period":"next"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart

## Chat with me

* holiday{"period":"next"}
    - slot{"period":"next"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"DATE":"tomorrow"}
    - slot{"DATE":"tomorrow"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart
* holiday{"period":"next"}
    - slot{"period":"next"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart

## apply request form

* leaveRequest{"time":"2019-09-28T00:00:00.000-07:00"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - action_leaveTypes
* leaveType{"leaveType":"cls"}
    - slot{"leaveType":"cls"}
    - request_apply_form
    - form{"name": "request_apply_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## apply request form

* leaveRequest{"DATE":"12-10-2019", "time":"2019-09-28T00:00:00.000-07:00"}
	- slot{"DATE":"12-10-2019"}
    - slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - action_leaveTypes
* leaveType{"leaveType":"cls"}
    - slot{"leaveType":"cls"}
    - request_apply_form
    - form{"name": "request_apply_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - slot{"reason":"going home"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## apply request form

* leaveRequest{"leaveType":"Cls"}
    - slot{"leaveType":"Cls"}
    - request_apply_form
    - form{"name": "request_apply_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - slot{"reason":"going home"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## apply request form

* leaveRequest{"leaveType":"Cls", "DATE":"12-10-2019", "time":"2019-09-28T00:00:00.000-07:00"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"leaveType":"Cls"}
    - request_apply_form
    - form{"name": "request_apply_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - slot{"reason":"going home"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## apply request form

* leaveRequest{"leaveType":"Cls", "DATE":"12-10-2019", "toDate":"next tuesday", "time":"2019-09-28T00:00:00.000-07:00"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - request_apply_form
    - form{"name": "request_apply_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - slot{"reason":"going home"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## apply request form

* leaveRequest{"DATE":"12-10-2019", "toDate":"next tuesday", "time":"2019-09-28T00:00:00.000-07:00"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - action_leaveTypes
* leaveType{"leaveType":"cls"}
    - slot{"leaveType":"cls"}
    - request_apply_form
    - form{"name": "request_apply_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - slot{"reason":"going home"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## Chat with me

* leaveRequest{"leaveType":"sick", "time":"2019-09-28T00:00:00.000-07:00"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"leaveType":"sick"}
    - request_apply_form
    - form{"name": "request_apply_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - slot{"reason":"going home"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## Chat with me

* leaveRequest{"DATE":"next tuesday","time":"2019-10-01T00:00:00.000-07:00"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"next tuesday"}
    - action_leaveTypes
* leaveType{"leaveType":"cls"}
    - slot{"leaveType":"cls"}
    - request_apply_form
    - form{"name": "request_apply_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - slot{"reason":"going home"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## holiday

* holiday{"time":"2019-09-28T00:00:00.000-07:00"}
    - action_is_holiday
    - utter_like_dislike
    - action_restart

## holiday

* holiday{"time":{"to":"2020-01-01T00:00:00.000-08:00","from":"2019-01-20T00:00:00.000-08:00"}}
    - action_is_holiday
    - utter_like_dislike
    - action_restart

## Current time Story

* current_time
    - action_time
    - utter_like_dislike
    - action_restart

## Current date Story

* current_date
    - action_date
    - utter_like_dislike
    - action_restart

## Current name Story

* my_name
    - action_name
    - utter_like_dislike
    - action_restart

## Current age Story

* my_age
    - action_age
    - utter_like_dislike
    - action_restart

## Current gender Story

* my_gender
    - action_gender
    - utter_like_dislike
    - action_restart

## Current location Story

* mylocation
    - action_location
    - utter_like_dislike
    - action_restart

## Current email Story

* my_email
    - action_email
    - utter_like_dislike
    - action_restart

## Current job descr Story

* my_job_description
    - action_job
    - utter_like_dislike
    - action_restart

## Current manager Story

* my_manager
    - action_manager
    - utter_like_dislike
    - action_restart

## Current job descr Story

* my_mobile
    - action_mobile
    - utter_like_dislike
    - action_restart

## Current manager Story

* my_tell_about_me
    - action_tell_about_me
    - utter_like_dislike
    - action_restart

## faqs

* faq
   - utter_genfaq
   - action_restart

## apply leave request

* leaveRequest
	- action_leaveTypes
* leaveType{"leaveType":"cls"}
    - slot{"leaveType":"cls"}
    - request_apply_form
    - form{"name": "request_apply_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
	- slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - slot{"reason":"going home"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## Benefits

* Benefits
    - utter_Benefits
    - utter_like_dislike
    - action_restart

## Policy travel

* policyTravel
    - utter_policyTravel
    - utter_like_dislike
    - action_restart

## News

* News
    - action_news
    - utter_like_dislike
    - action_restart

## Leave Calendar

* leaveCalendar
    - utter_leaveCalendar
    - utter_like_dislike
    - action_restart

## No query

* leaveNoQuery
    - utter_leaveNoQuery
    - utter_like_dislike
    - action_restart

## leave Advance

* leaveAdvanceDays
    - utter_LeaveAdvance
    - utter_like_dislike
    - action_restart

## benefits story

* benefits_esic
   - utter_benefits_esic
   - utter_like_dislike
   - action_restart

## benefits story

* not_reflect_esic
   - utter_not_reflect_esic
   - utter_like_dislike
   - action_restart

## benefits story

* yes_query
   - utter_yes_query
   - utter_like_dislike
   - action_restart

## benefits story

* reliefFund
   - utter_reliefFund
   - utter_like_dislike
   - action_restart

## benefits story

* no_query
   - utter_no_query
   - utter_like_dislike
   - action_restart

## benefits story

* esic_mandat
   - utter_esic_mandat
   - utter_like_dislike
   - action_restart

## benefits story

* not_reflect_uan_pf
   - utter_not_reflect_uan_pf
   - utter_like_dislike
   - action_restart

## benefits story

* merge_uan
   - utter_merge_uan
   - utter_like_dislike
   - action_restart

## benefits story

* update_kyc_pf
   - utter_update_kyc_pf
   - utter_like_dislike
   - action_restart

## benefits story

* employment_certificate
   - utter_employment_certificate
   - utter_like_dislike
   - action_restart

## benefits story

* it_services
   - utter_it_services
   - utter_like_dislike
   - action_restart

## benefits story

* travel_services
   - utter_travel_services
   - utter_like_dislike
   - action_restart

## benefits story

* band_changed_designation
   - utter_band_changed_designation
   - utter_like_dislike
   - action_restart

## benefits story

* suggest_tax
   - utter_suggest_tax
   - utter_like_dislike
   - action_restart

## benefits story

* uable_timesheet
   - utter_uable_timesheet
   - utter_like_dislike
   - action_restart

## benefits story

* pf_first_month
   - utter_pf_first_month
   - utter_like_dislike
   - action_restart

## benefits story

* noted_management
   - utter_noted_management
   - utter_like_dislike
   - action_restart

## benefits story

* plan_outings
   - utter_plan_outings
   - utter_like_dislike
   - action_restart

## benefits story

* hike_appraisal
   - utter_hike_appraisal
   - utter_like_dislike
   - action_restart

## benefits story

* designation_appraisal
   - utter_designation_appraisal
   - utter_like_dislike
   - action_restart

## benefits story

* eligible_appraisal
   - utter_eligible_appraisal
   - utter_like_dislike
   - action_restart

## benefits story

* min_hike
   - utter_min_hike
   - utter_like_dislike
   - action_restart

## benefits story

* review_preiod_appraisal
   - utter_review_preiod_appraisal
   - utter_like_dislike
   - action_restart

## benefits story

* calculate_rating
   - utter_calculate_rating
   - utter_like_dislike
   - action_restart

## benefits story

* shall_update
   - utter_shall_update
   - utter_like_dislike
   - action_restart

## benefits story

* edit_details
   - utter_edit_details
   - utter_like_dislike
   - action_restart

## benefits story

* enroll_medical
   - utter_enroll_medical
   - utter_like_dislike
   - action_restart

## benefits story

* enrol_mid
   - utter_enrol_mid
   - utter_like_dislike
   - action_restart

## benefits story

* upload_bills_portal
   - utter_upload_bills_portal
   - utter_like_dislike
   - action_restart

## benefits story

* claim_consultation
   - utter_claim_consultation
   - utter_like_dislike
   - action_restart

## benefits story

* ayurvedic_treatment
   - utter_ayurvedic_treatment
   - utter_like_dislike
   - action_restart

## benefits story

* changes_benefits_portal
   - utter_changes_benefits_portal
   - utter_like_dislike
   - action_restart

## benefits story

* two_wheeler_maintance
   - utter_two_wheeler_maintance
   - utter_like_dislike
   - action_restart

## benefits story

* fuel_reimbursement
   - utter_fuel_reimbursement
   - utter_like_dislike
   - action_restart

## benefits story

* petrol_vehicle_number
   - utter_petrol_vehicle_number
   - utter_like_dislike
   - action_restart

## benefits story

* claim_multicars
   - utter_claim_multicars
   - utter_like_dislike
   - action_restart

## benefits story

* taxreturns_query
   - utter_taxreturns_query
   - utter_like_dislike
   - action_restart

## benefits story

* benefits_tax_exemption
   - utter_benefits_tax_exemption
   - utter_like_dislike
   - action_restart

## benefits story

* insurance_family_open
   - utter_insurance_family_open
   - utter_like_dislike
   - action_restart

## benefits story

* cancel_zeta_card
   - utter_cancel_zeta_card
   - utter_like_dislike
   - action_restart

## benefits story

* valid_zeta_balance
   - utter_valid_zeta_balance
   - utter_like_dislike
   - action_restart

## benefits story

* premium_details
   - utter_premium_details
   - utter_like_dislike
   - action_restart

## benefits story

* add_benefits_portal
   - utter_add_benefits_portal
   - utter_like_dislike
   - action_restart

## benefits story

* ctc_offer
   - utter_ctc_offer
   - utter_like_dislike
   - action_restart

## benefits story

* lop_deduction
   - utter_lop_deduction
   - utter_like_dislike
   - action_restart

## benefits story

* lop_calculate
   - utter_lop_calculate
   - utter_like_dislike
   - action_restart

## benefits story

* contact_payroll_team
   - utter_contact_payroll_team
   - utter_like_dislike
   - action_restart

## benefits story

* emergency_leave
   - utter_emergency_leave
   - utter_like_dislike
   - action_restart

## benefits story

* received_hike_variable
   - utter_received_hike_variable
   - utter_like_dislike
   - action_restart

## benefits story

* relieved_early
   - utter_relieved_early
   - utter_like_dislike
   - action_restart

## benefits story

* docs_last_working
   - utter_docs_last_working
   - utter_like_dislike
   - action_restart

## benefits story

* last_working_credit
   - utter_last_working_credit
   - utter_like_dislike
   - action_restart

## benefits story

* NP_investments
   - utter_NP_investments
   - utter_like_dislike
   - action_restart

## benefits story

* buyout_option
   - utter_buyout_option
   - utter_like_dislike
   - action_restart

## Insurance policy

* policyInsurance
  - utter_policyInsurance
  - utter_like_dislike
  - action_restart

## leave Entitlement
* leaveEntitlement
   - utter_leaveEntitlement
   - utter_like_dislike
   - action_restart

## leave takes

* leaveTakes{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - action_leaveTakes
    - utter_like_dislike
    - action_restart

## leave takes

* leaveTakes{"DATE":"year"}
    - slot{"DATE":"year"}
    - action_leaveTakes
    - utter_like_dislike
    - action_restart

## Annual day

* annualDay
   - utter_annualDay
   - utter_like_dislike
   - action_restart

## doj

* my_doj
   - action_my_doj
   - utter_like_dislike
   - action_restart

## location with location slot

* mylocation{"location":"Bng"}
   - slot{"location":"Bng"}
   - action_location
   - utter_like_dislike
   - action_restart

## log Time

* logTime
   - utter_logTime
   - utter_like_dislike
   - action_restart

## contact Info

* contactInfo
   - utter_contactInfo
   - utter_like_dislike
   - action_restart

## open site

* openSite
   - utter_logTime    
   - utter_like_dislike
   - action_restart

## num numEmployees

* numEmployees
   - utter_numEmployees
   - utter_like_dislike
   - action_restart

## leave Encashment

* leaveEncashment
   - utter_leaveEncashment
   - utter_like_dislike
   - action_restart

## HR Team

* HRTeam
   - utter_HRTeam
   - utter_like_dislike
   - action_restart

## CEA Avail

* CEAAvail
   - utter_CEAAvail
   - utter_like_dislike
   - action_restart

## leave update request

* leaveUpdateRequest{"leaveType":"birthday", "leaveStatus":"A", "requestId":"123"}
    - slot{"leaveType":"birthday"}
    - slot{"leaveStatus":"A"}
    - slot{"requestId":"123"}
    - action_leaveUpdateRequest
    - utter_like_dislike
    - action_restart

## leave update request

* leaveUpdateRequest
   - action_leaveUpdateRequest
   - utter_like_dislike
   - action_restart

## leave update request

* leaveUpdateRequest{"leaveStatus":"A", "requestId":"123"}
    - slot{"leaveStatus":"A"}
    - slot{"requestId":"123"}
    - action_leaveUpdateRequest
    - utter_like_dislike
    - action_restart

## project list

* projectList
    - action_projectList
    - utter_like_dislike
    - action_restart

## project list

* projectList{"DATE":"tomorrow", "time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"tomorrow"}
    - action_projectList
    - utter_like_dislike
    - action_restart

## leave Approve list

* leaveApproveList
    - action_leaveApproveList
    - utter_like_dislike
    - action_restart

## leave Approve list

* leaveApproveList{"leaveType":"CL", "leaveStatus":"A"}
    - slot{"leaveType":"CL"}
    - slot{"leaveStatus":"A"}
    - action_leaveApproveList
    - utter_like_dislike
    - action_restart

## cancel request form

* leaveList{"time":"2019-09-28T00:00:00.000-07:00"}
    - action_leaveList
    - utter_like_dislike
    - action_restart

## leave list request form

* leaveList{"leaveStatus":"Submitted"}
    - slot{"leaveStatus":"Submitted"}
    - action_leaveList
    - utter_like_dislike
    - action_restart

## cancel request form

* leaveList{"DATE":"12-10-2019"}
    - slot{"DATE":"12-10-2019"}
    - action_leaveList
    - utter_like_dislike
    - action_restart

## cancel request form

* leaveList
    - action_leaveList
    - utter_like_dislike
    - action_restart

## cancel request form

* leaveList{"DATE":"12-10-2019", "time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - action_leaveList
    - utter_like_dislike
    - action_restart

## cancel request form

* leaveList{"leaveType":"Casual"}
    - slot{"leaveType":"Casual"}
    - action_leaveList
    - utter_like_dislike
    - action_restart

## cancel request form

* leaveList{"leaveType":"casual", "DATE":"12-10-2019", "time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"leaveType":"casual"}
    - action_leaveList
    - utter_like_dislike
    - action_restart

## leave Carry forwarded

* leaveCarryForwarded{"leaveType":"birthday"}
    - slot{"leaveType":"birthday"}
    - utter_leaveCarryForwarded
    - utter_like_dislike
    - action_restart

## fallback story

* out_of_scope
    - my_fallback_action

## Story from conversation with SP4130 on January 6th 2020
* current_date{"DATE":"current year","time":"2020-01-01T00:00:00.000+00:00"}
    - slot{"DATE":"current year"}
    - slot{"time":"2020-01-01T00:00:00.000+00:00"}
    - action_date
    - action_restart

## current time

* current_time{"DATE":"tomorrow","time":"2019-10-17T00:00:00.000-07:00"}
    - slot{"DATE":"tomorrow"}
    - slot{"time":"2019-10-17T00:00:00.000-07:00"}
    - action_time
    - utter_like_dislike
    - action_restart

## leave type days

* leaveTypeDays{"leaveType": "LOP"}
    - slot{"leaveType": "LOP"}
    - action_leaveTypeDays
    - utter_like_dislike
    - action_restart

## leave type days

* leaveTypeDays{"leaveType": "LOP", "DATE":"tomorrow"}
    - slot{"DATE":"tomorrow"}
    - slot{"leaveType": "LOP"}
    - action_leaveTypeDays
    - utter_like_dislike
    - action_restart

## leave type days

* leaveTypeDays{"leaveType": "LOP", "time":"tomorrow"}
    - slot{"time":"tomorrow"}
    - slot{"leaveType": "LOP"}
    - action_leaveTypeDays
    - utter_like_dislike
    - action_restart

## leave type days

* leaveTypeDays{"leaveType": "LOP", "DATE":"tomorrow", "time":"tomorrow"}
    - slot{"DATE":"tomorrow"}
    - slot{"time":"tomorrow"}
    - slot{"leaveType": "LOP"}
    - action_leaveTypeDays
    - utter_like_dislike
    - action_restart

## leave Approve list

* leaveApproveList{"leaveType":"CL"}
    - slot{"leaveType":"CL"}
    - action_leaveApproveList
    - utter_like_dislike
    - action_restart

## leave Approve list

* leaveApproveList{"leaveStatus":"A"}
    - slot{"leaveStatus":"A"}
    - action_leaveApproveList
    - utter_like_dislike
    - action_restart

## leave list request form

* leaveList{"leaveStatus":"Submitted", "leaveType":"WFH"}
    - slot{"leaveType":"WFH"}
    - slot{"leaveStatus":"Submitted"}
    - action_leaveList
    - utter_like_dislike
    - action_restart

## policies

* help_policies
   - utter_help_policies
   - action_restart

## Leave FAQS

* Leave_FAQs
   - utter_Leave_FAQs
   - action_restart

## EWH FAQS

* EWH_FAQs
   - utter_EWH_FAQs
   - action_restart

## Benefits FAQS

* Benefits_FAQs
   - utter_Benefits_FAQs
   - action_restart

## Satutory FAQS

* Satutory_FAQs
   - utter_Satutory_FAQs
   - action_restart

## Comp off FAQS

* ComOff_FAQs
   - utter_ComOff_FAQs
   - action_restart

## flexi benefits

* flexi_benefits
   - utter_flexi_benefits
   - utter_like_dislike
   - action_restart

## activate UAN

* activate_UAN
   - utter_activate_UAN
   - utter_like_dislike
   - action_restart

## investment declare

* investment_declare
   - utter_investment_declare
   - utter_like_dislike
   - action_restart

## days in a month EWC
* month_EWC
   - utter_month_EWC
   - utter_like_dislike
   - action_restart

## cutoff days in EWC

* EWC_cutoff
   - utter_EWC_cutoff
   - utter_like_dislike
   - action_restart

## travel request form

* travelRequest
    - action_travelRecentSlots
* location{"requestId": "123,1234", "projectName": "Speridian India - Innovation Lab HR Bot", "location": ["Bangalore", "Mumbai"]}
    - slot{"location":["Bangalore","mumbai"]}
    - slot{"requestId":"123,1234"}
    - slot{"projectName":"Speridian India - Innovation Lab HR Bot"}
    - request_travel_form
    - form{"name": "request_travel_form"}
    - form{"name": null}
    - action_travelSlots_values
* confirm{"confirm":"confirm"}
    - action_travelRequest_apply
    - utter_like_dislike
    - action_restart

## Story from conversation with SP2842 on February 12th 2020
* travelRequest{"location":"mumbai"}
    - slot{"location":["chennai","mumbai"]}
    - request_travel_form
    - form{"name": "request_travel_form"}
    - form{"name": null}
    - action_travelSlots_values
* confirm{"confirm":"confirm"}
    - action_travelRequest_apply
    - utter_like_dislike
    - action_restart

## Story from conversation with SP2842 on February 12th 2020
* travelRequest{"location":"mumbai", "DATE":"tomorrow"}
    - slot{"location":["chennai","mumbai"]}
    - slot{"DATE":"tomorrow"}
    - request_travel_form
    - form{"name": "request_travel_form"}
    - form{"name": null}
    - action_travelSlots_values
* confirm{"confirm":"confirm"}
    - action_travelRequest_apply
    - utter_like_dislike
    - action_restart

## Story from conversation with SP2842 on February 12th 2020
* travelRequest{"location":"mumbai", "DATE":"tomorrow", "time":"February 12th 2020"}
    - slot{"location":["chennai","mumbai"]}
    - slot{"DATE":"tomorrow"}
    - slot{"time":"February 12th 2020"}
    - request_travel_form
    - form{"name": "request_travel_form"}
    - form{"name": null}
    - action_travelSlots_values
* confirm{"confirm":"confirm"}
    - action_travelRequest_apply
    - action_restart

## leave takes

* leaveTakes{"leaveType":"ED"}
    - slot{"leaveType":"ED"}
    - action_leaveTakes
    - utter_like_dislike
    - action_restart

## leave handle FAQS

* leaveHandle_FAQS{"number":"1"}
    - slot{"number":"1"}
    - action_FAQs_handle
    - utter_like_dislike
    - action_restart

## leave handle FAQS

* leaveHandle_FAQS{"number":"2"}
    - slot{"number":"2"}
    - action_FAQs_handle
    - utter_like_dislike
    - action_restart

## home button

* home
   - action_home
   - action_restart

## travel request form

* travelRequest
    - action_travelRecentSlots
* location{"location": ["Bangalore", "Mumbai"]}
    - slot{"location":["Bangalore","mumbai"]}
    - request_travel_form
    - form{"name": "request_travel_form"}
    - form{"name": null}
    - action_travelSlots_values
* confirm{"confirm":"confirm"}
    - action_travelRequest_apply
    - utter_like_dislike
    - action_restart

## travel request form and to Locations

* travelRequest
    - action_travelRecentSlots
* location{"requestId": "123,1234", "projectName": "Speridian India - Innovation Lab HR Bot", "location": "Bangalore", "toLocation": "Mumbai"}
    - slot{"location":["Bangalore","mumbai"]}
    - slot{"requestId":"123,1234"}
    - slot{"projectName":"Speridian India - Innovation Lab HR Bot"}
    - request_travel_form
    - form{"name": "request_travel_form"}
    - form{"name": null}
    - action_travelSlots_values
* confirm{"confirm":"confirm"}
    - action_travelRequest_apply
    - utter_like_dislike
    - action_restart

## login details

* login
   - action_login
   - action_restart

## better answer

* weather
   - action_weather
   - utter_like_dislike
   - action_restart

## travel request form

* travelRequest
    - action_travelRecentSlots
* location
    - request_travel_form
    - form{"name": "request_travel_form"}
    - form{"name": null}
    - action_travelSlots_values
* confirm{"confirm":"confirm"}
    - action_travelRequest_apply    
    - utter_like_dislike
    - action_restart

## leave Advance

* LeaveAdvance
    - utter_LeaveAdvance
    - utter_like_dislike
    - action_restart

## leave policy

* policyLeave{"leaveType":"maternity"}
  - slot{"leaveType":"maternity"}
  - utter_policy
  - utter_like_dislike
  - action_restart

## Story from conversation with SP2014 on September 3rd 2020

* leaveRequest{"leaveType":"casual","DATE":"next monday","time":"2020-09-07T00:00:00.000+00:00"}
    - slot{"DATE":"next monday"}
    - slot{"leaveType":"casual"}
    - slot{"time":"2020-09-07T00:00:00.000+00:00"}
    - slot{"DATE":"next monday"}
    - slot{"leaveType":"casual"}
    - slot{"time":"2020-09-07T00:00:00.000+00:00"}
    - request_apply_form
    - form{"name": "request_apply_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
  - slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - slot{"reason":"going home"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## Story from conversation with SP2014 on September 3rd 2020

* leaveRequest{"leaveType":"casual"}
    - slot{"leaveType":"casual"}
    - request_apply_form
    - form{"name": "request_travel_form"}
    - form{"name": null}
    - action_slots_values
* confirm{"confirm":"confirm"}
  - slot{"time":"2019-09-28T00:00:00.000-07:00"}
    - slot{"DATE":"12-10-2019"}
    - slot{"toDate":"next tuesday"}
    - slot{"leaveType":"Cls"}
    - slot{"reason":"going home"}
    - action_leave_apply
    - utter_like_dislike
    - action_restart

## Story from conversation with SP2014 on September 3rd 2020

* leaveRequest
    - action_leaveTypes
* leaveType{"leaveType":"SL"}
    - slot{"leaveType":"SL"}
    - slot{"leaveType":"SL"}
    - request_apply_form
    - form{"name":"request_apply_form"}
    - slot{"leaveType":"sick leave"}
    - slot{"reason":"Not feeling well"}
    - slot{"leaveType":"sick leave"}
    - slot{"reason":"Not feeling well"}
    - slot{"requested_slot":"DATE"}
* date{"DATE":"2020","time":{"to":"2020-09-12T00:00:00.000+00:00","from":"2020-09-10T00:00:00.000+00:00"}}
    - slot{"DATE":"2020"}
    - slot{"time":{"to":"2020-09-12T00:00:00.000+00:00","from":"2020-09-10T00:00:00.000+00:00"}}
    - slot{"DATE":"2020"}
    - slot{"time":{"to":"2020-09-12T00:00:00.000+00:00","from":"2020-09-10T00:00:00.000+00:00"}}
    - request_apply_form
    - slot{"toDate":"Sep 11, 2020"}
    - slot{"DATE":"Sep 10, 2020"}
    - form{"name":null}
    - slot{"requested_slot":null}
    - action_slots_values
* confirm{"confirm":"confirm"}
    - slot{"confirm":"confirm"}
    - slot{"confirm":"confirm"}
    - action_leave_apply
    - utter_like_dislike
    - slot{"leaveType":"SL"}
    - slot{"DATE":"2020"}
    - slot{"time":{"to":"2020-09-12T00:00:00.000+00:00","from":"2020-09-10T00:00:00.000+00:00"}}
    - slot{"confirm":"confirm"}
    - action_restart

## Story from conversation with SP2014 on September 3rd 2020

* leaveRequest
    - action_leaveTypes
* leaveType{"leaveType":"BDL"}
    - slot{"leaveType":"BDL"}
    - slot{"leaveType":"BDL"}
    - request_apply_form
    - form{"name":"request_apply_form"}
    - slot{"leaveType":"Birthday leave"}
    - slot{"reason":"Birthday leave"}
    - slot{"leaveType":"Birthday leave"}
    - slot{"reason":"Birthday leave"}
    - slot{"requested_slot":"DATE"}
* date{"DATE":"2020","time":{"to":"2020-09-12T00:00:00.000+00:00","from":"2020-09-10T00:00:00.000+00:00"}}
    - slot{"DATE":"2020"}
    - slot{"time":{"to":"2020-09-12T00:00:00.000+00:00","from":"2020-09-10T00:00:00.000+00:00"}}
    - slot{"DATE":"2020"}
    - slot{"time":{"to":"2020-09-12T00:00:00.000+00:00","from":"2020-09-10T00:00:00.000+00:00"}}
    - request_apply_form
    - slot{"toDate":"Sep 11, 2020"}
    - slot{"DATE":"Sep 10, 2020"}
    - form{"name":null}
    - slot{"requested_slot":null}
    - action_slots_values
* confirm{"confirm":"confirm"}
    - slot{"confirm":"confirm"}
    - slot{"confirm":"confirm"}
    - action_leave_apply
    - utter_like_dislike
    - slot{"leaveType":"BDL"}
    - slot{"DATE":"2020"}
    - slot{"time":{"to":"2020-09-12T00:00:00.000+00:00","from":"2020-09-10T00:00:00.000+00:00"}}
    - slot{"confirm":"confirm"}
    - action_restart

## employeeQuery

* employee_query
   - action_employeeQuery
   - action_restart

## employeeQuery with person

* employee_query{"person":"priyank"}
   - slot{"person":"priyank"}
   - action_employeeQuery
   - action_restart

## employeeQuery with location

* employee_query{"location":"mumbai"}
   - slot{"location":"mumbai"}
   - action_employeeQuery
   - action_restart

## employeeSearch

* employee_search
   - utter_employeeSearch
   - action_restart

## New Story

* yes_query{"time":{"to":"2020-01-01T00:00:00.000+00:00","from":null}}
    - slot{"time":{"to":"2020-01-01T00:00:00.000+00:00","from":null}}
    - utter_yes_query
    - utter_like_dislike
    - action_restart

## previous conversations
* previous_conversations
    - action_previous_conversations
    - action_restart

## it_outlook_problems 1
* it_outlook_problems
    - utter_it_outlook
    - action_restart

## it_outlook_problems 2
* it_outlook_login
    - utter_it_outlook1
* confirm
    - utter_it_outlook2
* confirm
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook_problems 3
* it_outlook_login
    - utter_it_outlook1
* confirm
    - utter_it_outlook2
* deny
    - utter_it_outlook3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook_problems 4
* it_outlook_login
    - utter_it_outlook1
* deny
    - utter_it_outlook12
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook_problems 5
* it_outlook_login
    - utter_it_outlook1
* deny
    - utter_it_outlook12
* deny
    - utter_it_outlook2
* confirm
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook_problems 6
* it_outlook_login
    - utter_it_outlook1
* deny
    - utter_it_outlook12
* deny
    - utter_it_outlook2
* deny
    - utter_it_outlook3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook 1
* it_outlooknotworking
    - utter_it_outlook0
* it_outlook_restart
    - utter_it_outlook11
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook 2
* it_outlooknotworking
    - utter_it_outlook0
* it_outlook_restart
    - utter_it_outlook11
* deny
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook 3
* it_outlooknotworking
    - utter_it_outlook0
* it_outlook_not_opening
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook 4
* it_outlook_email_not_syncing
    - utter_it_outlook10
* confirm
    - utter_it_outlook1
* deny
    - utter_it_outlook12
* deny
    - utter_it_outlook2
* deny
    - utter_it_outlook3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook 5
* it_outlook_email_not_syncing
    - utter_it_outlook10
* confirm
    - utter_it_outlook1
* deny
    - utter_it_outlook12
* deny
    - utter_it_outlook2
* confirm
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook 6
* it_outlook_email_not_syncing
    - utter_it_outlook10
* confirm
    - utter_it_outlook1
* deny
    - utter_it_outlook12
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook 7
* it_outlook_email_not_syncing
    - utter_it_outlook10
* confirm
    - utter_it_outlook1
* confirm
    - utter_it_outlook2
* deny
    - utter_it_outlook3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook 8
* it_outlook_email_not_syncing
    - utter_it_outlook10
* confirm
    - utter_it_outlook1
* confirm
    - utter_it_outlook2
* confirm
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook 9
* it_outlook_email_not_syncing
    - utter_it_outlook10
* deny
    - utter_it_outlook7
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook 10
* it_outlook_email_not_syncing
    - utter_it_outlook10
* deny
    - utter_it_outlook7
* deny
    - utter_it_outlook5
* confirm
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook 11
* it_outlook_email_not_syncing
    - utter_it_outlook10
* deny
    - utter_it_outlook7
* deny
    - utter_it_outlook5
* deny
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook a
* it_outlook_offline
    - utter_it_outlook8
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook b
* it_outlook_offline
    - utter_it_outlook8
* deny
    - utter_it_outlook4
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook c
* it_outlook_offline
    - utter_it_outlook8
* deny
    - utter_it_outlook4
* deny
    - utter_it_outlook3
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook_archive
* it_outlookarchivehelp
    - utter_it_outlooka
* confirm
    - utter_it_outlooke
* confirm
    - utter_it_outlookf
* confirm
    - utter_it_outlookg
* confirm
    - utter_it_outlookh
* confirm
    - utter_it_outlookd
* confirm
    - utter_it_outlookj
* confirm
    - utter_it_outlookk
* confirm
    - utter_it_outlookl
* confirm
    - utter_it_outlookm
* confirm
    - utter_it_outlookn
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook_archive 1
* it_outlookarchivehelp
    - utter_it_outlooka
* confirm
    - utter_it_outlooke
* confirm
    - utter_it_outlookf
* confirm
    - utter_it_outlookg
* confirm
    - utter_it_outlookh
* confirm
    - utter_it_outlookd
* confirm
    - utter_it_outlookj
* confirm
    - utter_it_outlookk
* confirm
    - utter_it_outlookl
* confirm
    - utter_it_outlookm
* confirm
    - utter_it_outlookn
* deny
    - utter_it_outlooko
* confirm
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook_archive 2
* it_outlookarchivehelp
    - utter_it_outlooka
* confirm
    - utter_it_outlooke
* confirm
    - utter_it_outlookf
* confirm
    - utter_it_outlookg
* confirm
    - utter_it_outlookh
* confirm
    - utter_it_outlookd
* confirm
    - utter_it_outlookj
* confirm
    - utter_it_outlookk
* confirm
    - utter_it_outlookl
* confirm
    - utter_it_outlookm
* confirm
    - utter_it_outlookn
* deny
    - utter_it_outlooko
* deny
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook_archive 3
* it_outlookarchivehelp
    - utter_it_outlooka
* confirm
    - utter_it_outlooke
* confirm
    - utter_it_outlookf
* confirm
    - utter_it_outlookg
* confirm
    - utter_it_outlookh
* confirm
    - utter_it_outlookd
* deny
    - utter_it_outlooki
* confirm
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_outlook_archive 4
* it_outlookarchivehelp
    - utter_it_outlooka
* confirm
    - utter_it_outlooke
* confirm
    - utter_it_outlookf
* confirm
    - utter_it_outlookg
* confirm
    - utter_it_outlookh
* confirm
    - utter_it_outlookd
* deny
    - utter_it_outlooki
* deny
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook_archive 5
* it_outlookarchivehelp
    - utter_it_outlooka
* deny
    - utter_it_outlookb
* deny
    - utter_it_outlookc
* deny
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_outlook_archive 6
* it_outlookarchivehelp
    - utter_it_outlooka
* deny
    - utter_it_outlookb
* deny
    - utter_it_outlookc
* confirm
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_configure_outlook
* it_configure_outlook
    - utter_it_outlook1a
* confirm
    - utter_it_outlook1b
* confirm
    - utter_it_outlook1d
* confirm
    - utter_it_outlook1e
* confirm
    - utter_it_outlook1f
* confirm
    - utter_it_outlook1g
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_configure_outlook 2
* it_configure_outlook
    - utter_it_outlook1a
* confirm
    - utter_it_outlook1b
* confirm
    - utter_it_outlook1d
* confirm
    - utter_it_outlook1e
* confirm
    - utter_it_outlook1f
* confirm
    - utter_it_outlook1g
* deny
    - utter_it_outlook1h
* deny
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_configure_outlook 3
* it_configure_outlook
    - utter_it_outlook1a
* confirm
    - utter_it_outlook1b
* confirm
    - utter_it_outlook1d
* confirm
    - utter_it_outlook1e
* confirm
    - utter_it_outlook1f
* confirm
    - utter_it_outlook1g
* deny
    - utter_it_outlook1h
* confirm
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_configure_outlook
* it_outlookarchivehelp
    - utter_it_outlooka
* deny
    - utter_it_outlookb
* confirm
    - utter_it_outlook1a
* confirm
    - utter_it_outlook1b
* confirm
    - utter_it_outlook1d
* confirm
    - utter_it_outlook1e
* confirm
    - utter_it_outlook1f
* confirm
    - utter_it_outlook1g
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_configure_outlook 2
* it_outlookarchivehelp
    - utter_it_outlooka
* deny
    - utter_it_outlookb
* confirm
    - utter_it_outlook1a
* confirm
    - utter_it_outlook1b
* confirm
    - utter_it_outlook1d
* confirm
    - utter_it_outlook1e
* confirm
    - utter_it_outlook1f
* confirm
    - utter_it_outlook1g
* deny
    - utter_it_outlook1h
* deny
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_configure_outlook 3
* it_outlookarchivehelp
    - utter_it_outlooka
* deny
    - utter_it_outlookb
* confirm
    - utter_it_outlook1a
* confirm
    - utter_it_outlook1b
* confirm
    - utter_it_outlook1d
* confirm
    - utter_it_outlook1e
* confirm
    - utter_it_outlook1f
* confirm
    - utter_it_outlook1g
* deny
    - utter_it_outlook1h
* confirm
    - utter_it_outlook6
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_lan_cable_no_internet
* it_lan_cable_no_internet
    - utter_it_lan_cable_no_internet1
* deny
    - utter_it_lan_cable_no_internet2
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## it_lan_cable_no_internet2
* it_lan_cable_no_internet
    - utter_it_lan_cable_no_internet1
* confirm
    - utter_it_lan_cable_no_internet3
* confirm
    - utter_it_lan_cable_no_internet5
* confirm
    - utter_it_closing
    - utter_like_dislike
    - action_restart

## it_lan_cable_no_internet3
* it_lan_cable_no_internet
    - utter_it_lan_cable_no_internet1
* confirm
    - utter_it_lan_cable_no_internet3
* confirm
    - utter_it_lan_cable_no_internet5
* deny
    - utter_it_lan_cable_no_internet4
    - action_it_ticket_update
    - utter_like_dislike
    - action_restart

## theme Color

* themeColor
    - action_themeColor
    - action_restart

## theme Color with slot

* themeColor{"color":"blue"}
    - slot{"color":"blue"}
    - action_themeColor
    - action_restart

## theme Color with slot

* themeColor{"color":"red"}
    - slot{"color":"red"}
    - action_themeColor
    - action_restart

## restart

* restart
    - action_restart
