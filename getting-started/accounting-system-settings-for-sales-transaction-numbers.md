# Accounting - System Settings for Sales Transaction Numbers

The purpose of this article is point out some of the System Settings that can be used to control how Trans #'s within sale transactions can be auto generated.

To review system settings available, navigate to **System > Setup > System Settings**, then review the system settings shown below to determine which options may suite your business requirements.  &#x20;

**AUTONMBR** - Enabling this setting, by putting a checkmark in the **Enabled?** box, will result in automatically assigning transaction numbers to pending sale transactions.  Transaction numbers will be formatted as:  Office Code-YY-ZZZZZ, where **Office Code** is defined in **System > Setup > Offices**, YY is the last two digits of the current calendar year, and ZZZZZ is the number that will increment by 1 (one) as each new sale is added.     &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/b9009433-cd68-47b7-b8e3-7197a769cfbd)

Note:  The transaction number cannot exceed 16 characters.  If it exceeds 16 characters you will need to reduce the **Office Code** from 8 characters to 7 characters, if you utilize system setting **USE DASHES** in the transaction number.  You will receive the following **Save** **Sale Transaction** error message, if the **Office Code** has 8 characters.     &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/54da8a84-3fb6-4012-ab08-ec9357be4d01)

**USEDASHES** - Enabling this setting, by putting a checkmark in the **Enabled?** box, will insert dashes (-) into the automatically assigned sale transaction numbers.  If the **Enabled?** box is unchecked, the sale transaction number will generate without dashes. &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/98556087-242c-4b35-abdb-fd33b1e6d720)v

**OFFNUMSEQ** - Enabling this setting, by putting a checkmark in the **Enabled?** box, will result in one sequential number for each new sale transaction, instead of a sequential number by **Office Code**.  If this setting code is not enabled, the last 5 digits of each sale transaction number will be used only once, for example, AA-24-**00001**, BB-24-**00002**, AA\*\*-\*\*24-**00003**, CC-24-**00004**, etc. regardless of the **Office Code**.  If this setting code is enabled, the last 5 digits of each sale will be used for each **Office Code**, for example, AA-24-**00001**, BB-24-**00001**, AA-24-**00002**, CC-24-**00001**    &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/0066e5a1-75c6-44ee-a240-cc786959ac95)

**SALENEXTNUM** - The **Numeric Value** inserted will determine what the last 5 digits of the next sale transaction should be.  For example, if the **Numeric Value** entered is "1", when adding the next sale transaction, the last 5 digits of the sale transaction number will be "00001", if "125" is entered into the **Numeric Value** field, the last 5 digits of the next sale transaction number will be "00125". &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/ab46dba2-f06b-49e9-ab27-0063a54a2029)

Note:  This value can also be entered, in the **Next Sale Trans Number** field in the office profile record/s, by navigating to **System > Setup > Offices**.  Entering the values from the office profile record, will allow you to select a different value per office. &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/c101acad-c99e-44b9-929d-bb486f0cf50f)
