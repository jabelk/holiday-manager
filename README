# Happy Holidays from Cisco NSO

```
admin@ncs# show running-config list-of-holidays
list-of-holidays Christmas
 holiday-message "Merry Christmas!"
!
list-of-holidays Generic
 holiday-message "Happy Holidays!"
!
list-of-holidays Hanukkah
 holiday-message "Happy Hanukkah!"
!
list-of-holidays Kwanzaa
 holiday-message "Happy Kwanzaa"
!
list-of-holidays "New Year's Day"
 holiday-message "Happy New Years!"
!
admin@ncs# show running-config list-of-holidays | display json
{
  "data": {
    "holiday-manager:list-of-holidays": [
      {
        "holiday": "Christmas",
        "holiday-message": "Merry Christmas!"
      },
      {
        "holiday": "Generic",
        "holiday-message": "Happy Holidays!"
      },
      {
        "holiday": "Hanukkah",
        "holiday-message": "Happy Hanukkah!"
      },
      {
        "holiday": "Kwanzaa",
        "holiday-message": "Happy Kwanzaa"
      },
      {
        "holiday": "New Year's Day",
        "holiday-message": "Happy New Years!"
      }
    ]
  }
}
```
