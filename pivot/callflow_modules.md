Callflow Modules
=========

* cf_acdc_agent: Manipulate Call Center Agents (Login, Logout, Pause)
* cf_acdc_member: Manipulate memberships to Call Center Queues (Add Agent, Remove Agent)
* cf_acdc_queue: Manipulate Call Center Queue Settings
* cf_after_bridge: 
* cf_callflow: Execute another existing callflow
* cf_call_forward: Enable Call Forwarding
* cf_camping_feature: Camp on an extension (i.e. Callback when the extension is free)
* cf_check_cid: Check + route based on specific CallerID
* cf_cidlistmatch: Fork callflow destination based on source Caller ID Area code matching (i.e. East/West routing)
* cf_collect_dtmf: Collect DTMF Digits and store in a variable
* cf_conference: Send call to conference room
* cf_device: Send call to a specific VoIP Device
* cf_directory: Send call to Company Directory
* cf_disa: Request PIN Code, and present caller with Dialtone for dial-out purposes.
* cf_do_not_disturb: Enable/Disable Do not Disturb
* cf_dynamic_cid: Modify outgoing Caller ID Name or Number, dynamically
* cf_eavesdrop: Listen in (whisper/barge) on an existing call
* cf_faxbox: Deliver call to a Fax Box (like a voicemail box but for faxes)
* cf_fax_detect: Detect whether or not a fax is being requested
* cf_group: Deliver call to a group of users
* cf_intercept: Intercept a ringing call at another location
* cf_intercom: Intercom and Paging to an extension
* cf_language: Change the default language for the remainder of the call
* cf_manual_presence: Modify a BLF/Presence indicator light status
* cf_menu: Deliver call to a Menu
* cf_move: Move call to another media server
* cf_offnet: Send an outgoing call to the PSTN
* cf_page_group: Page a group of extensions
* cf_park: Park call for retrieval at another extension
* cf_pivot: Execute a pivot URL
* cf_play: Play media file
* cf_prepend_cid: Prepend caller ID Name or Number
* cf_privacy: Set the Privacy header so outgoing calls display "Unknown"
* cf_receive_fax: Force-receive a Fax
* cf_record_caller: Record audio, but only for the caller's side
* cf_record_call: Record audio for both sides
* cf_ring_group: Send call to a ring group of extensions
* cf_send_dtmf: Generate DTMF to the caller
* cf_sleep: Generate a delay/sleep/wait period
* cf_temporal_route: Execute callflows evaluated against time periods (ie Open / Closed hours)
* cf_tts: Text to Speech module
* cf_user: Ring a User (specifically, ring every device that a user owns)
* cf_voicemail: Send call to Voicemail
* cf_webhook: Register a webhook
