Assign the release channel's process end date to the pickings as scheduled date:

#. Assign a timezone on the Warehouse address if defined and if needed
   If you have a lot of warehouses in the same timezone, you can also define
   the timezone on the company partner.
   If you don't define a timezone on the warehouse(s) nor the company, the process
   end time on channels will be considered as UTC.
#. Propagate/update scheduled date of picking follow process end date/time automatically
   by setting "Update Scheduled Date" configuration in Settings/General Settings/Inventory

#. Go To Release Channels
#. Set an end time
#. Wake up the channel
#. The assigned pickings have their scheduled date set at the next end time. (if enabled "Update Scheduled Date" config)

When the assigned pickings are released, the move date deadline is set to the scheduled date
into the pickings generated by the release process.
