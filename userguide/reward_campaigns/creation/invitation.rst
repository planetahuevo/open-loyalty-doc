.. index::
   single: invitation

Invitation for the event
========================

You can offer for your customer as a reward invitation for business & corporate events or other depending on your business, e.g. conference. Customer need to "buy" reward, using his Active points pool. Cost of this reward is specified during creation in **Cost in points** field.

During creation you can also specified if all customers will received the same coupon code, or different one and limits of reward redemption (in general and per customer) 

**For example**

- if limit in general is equal to 10, limit per customer is equal to 1 and *single coupon* **marked** - then only the first ten clients will be able to use the invitation (each of them only once) and the invitation's coupon code will be the same for everyone
 
- if limit in general is equal to 10, limit per customer is equal to 1 and *single coupon* **unmarked** - then only the first ten clients will be able to use the invitation (each of them only once) and the invitation's coupon code will be different. 

Number of codes depends on number of uploaded coupon codes during reward creation e.g. if you uploaded 2 different codes, only those two will be randomly assigned to those customers. Another words, there can be situation that several of them receive the same codes. 

.. tip:: 

    **To avoid situation that some of customers can receive the same coupon code, upload as many different coupon codes as the limit in general**

To create Invitation for the event reward:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Tap **Reward campaigns** on the Admin sidebar and choose **Add reward campaign**. You can also add new reward directly from **All reward campaigns** list by clicking ``Add reward campaign`` at the top of the page 

.. image:: /userguide/_images/add_reward_button.png
   :alt:   Add Reward Options  

2. In the **Campaign type** section select an **Invitation for the event** reward type from a dropdown list (Discount code is displayed by default)

.. image:: /userguide/_images/invitation_type.PNG
   :alt:   Invitation for the event type

.. note:: 

    Depending on the selected **Campaign type**, a Basic information and next section - Campaign details, will display different fields to fill in.
    
    Different fields are required for *Cashback, Custom reward and Percentage discount code* , than for other types i.e. discount code, free delivery etc.  

.. image:: /userguide/_images/discount_basic2.PNG
   :alt:   Invitation Basic Information


3. When you choose *Invitation for the event*, in the **Basic information** section related to the default language version do the following    

 - Enter unique reward **Name**
 - If needed, provide a **Short description** of the reward campaign detail using rich media format 
 - If applicable, in **Condition description** field, provide a description of the conditions of getting a reward using rich media format
 - If applicable, enter description **How to use coupons** codes, to display on the storefront instructions how to get/use reward for customers   
 - If needed, in **Brand name** field provide the name of the brand, that will be display in Client cockpit
 - If needed, provide a **Brand description** of the reward campaign using rich media format
 - If applicable, fulfill the same fields in other language version e.g. polish as on a screen above 

.. image:: /userguide/_images/details_discount.PNG
   :alt:   Invitation Campaign Details 


4. In the **Campaign details** section do the following

 - To make reward available for customer, in **Active** field select "**Active**" from the dropdown list
 - If needed, enter URL to the content page in **More information link field**, that explains your reward campaign or to external web with reward details 
 - If applicable, in **Push notification text** provide a text message that will be displayed as a push notification for Customer, when reward becomes available for him
 - In **Cost in points** field, enter the number of points represented by the reward to define how many points customer needs to spend to get a reward
 - If applicable, In **Reward value** field provide a monetary value of reward
 - If needed, enter **Tax** rate that applies to the reward and monetary value of tax for reward in **Tax value**
 - If applicable, mark **Featured** checkbox to differentiate campaign from the others. **Feature is used when you want to filter campaigns using API**
 - If applicable, mark **Public** checkbox to differentiate campaign from the others. **Feature is used when you want to filter campaigns using API** 

.. note::

    If **Push notification text** is not provided, notification about new reward availability will not be displayed.

    It does not change the fact that the reward will be available for customer and display in **Available rewards** section in Admin and Client cockpit.


5. In the same **Campaign details** section, if applicable, create **Label(s)** you want refer to reward. Labels are intended to be used to specify identifying attributes of reward campaign. 
 
   Labels can be used only when you use API to organize subsets of rewards and make filtering/searching rewards campaign easier.  Through API you will be able to get list of all rewards with specified key or key and value. 
   
 - To create Label, tap ``Add Label`` and do the following: 
  - Type label **Key**, which is a label name
  - Type label **Value**
      
    For example: Key – Event, Value – Birthday. 
          
 - Repeat the process for all labels you want to used in your Loyalty Program
  
.. image:: /userguide/_images/reward_label.png
   :alt:   Reward Campaign Labels    
   
.. note:: 

    Filtering/Searching via API allows you to get list of all rewards related to events or (more specified) related to birthday event. 
    
.. note:: 

    Labels can be added to reward campaign during reward creation and subsequently added and modified at any time 


6. In the same **Campaign details** section, in **Categories** field, select campaign category or categories to be assign to this reward campaign. You can assign more than one campaign category. 

.. image:: /userguide/_images/reward_category.png
   :alt:   Campaign category    


7. **Brand info** section allows to upload an image of the reward brand, that will be display in Client cockpit

.. image:: /userguide/_images/reward_brand.png
   :alt:   Brand info 


8. A reward can be extended to members of a specific customer group. In the **Target** section identify the customer group that qualifies to receive the reward

 - In **Target type** field, select from dropdown list Level or Segment to specify whether the reward will be available for customers assigned to particular level or segment
 - Depending on selected *Target type*, field **Segments** to specify segments or **Levels** to specify levels appear.  You can choose one or more levels/segments to used

.. image:: /userguide/_images/reward_target.png
   :alt:   Target


9. To limit the number of times each customer can redeem reward, enter the number of usage limits in **Limit** section. *To limit the number of times the reward can be redeemed*, complete the limits in **Limit** section: 

 - In **Limit** field, define how many times reward could be redeemed during time boundaries from Activity section
 - In **Limit per customer** field, define how many times reward could be redeemed by one customer during time boundaries from Activity section
 - For unlimited use, mark **Use of the coupon code is not limited** checkbox. When you choose that option *Limit* and *Limit per customer* fields will not be available 
 - Mark **Single Coupon** checkox to assign the same coupon code for all customers. Unmarked checkbox means that customers receive different coupon codes (depedning on number uploaded in **Coupons** section) 
 
.. image:: /userguide/_images/reward_limit.png
   :alt:   Limit 


10. Add batch of **Coupons** to be used with the reward. 

    Type manually a **Coupons codes** to be used by customer or **Upload coupons** list of codes from CSV file. 

 - In **Days inactive** define number of days during which coupons assign to this campaign will be inactive since the transaction date.

   **If you want make coupons valid instantly, provide 0**

 - In **Days valid** specify number of days during which coupon assign to this campaign will be active since the inactive time boundaries finished. After provided here number of days voucher will expired.

   **If you want your coupons never expired, provide 0**

.. image:: /userguide/_images/coupons.PNG
   :alt:   Coupons  

.. note:: 

    Uploaded Coupon codes will not be displayed to customers on a storefront in Client Cockpit (after reward redemption).
    They will be visible from the admin in the **Redeemed reward** grid.
 

11. To make the reward *visible on the storefront for a limited period of time*, complete the **From and To dates** in **Visibility** section

 - In **Visible from** field set the first date the reward is visible. You can either enter the date or select it from the calendar
 - In **Visible to** field set the last date the reward is visible. You can either enter the date or select it from the calendar
 - If you want the reward to be visible all the time mark **All time visible** checkbox. When you choose that option *Visible from and Visible to fields will not be available*. 

.. image:: /userguide/_images/reward_visibility.png
   :alt:   Reward Visibility

.. note:: 

    **Visible to** and **Visible from** fields are available only when reward visibility is limited


12. **Activity** section define time boundaries when reward can be used by customers. To make the reward *available for a limited period of time*, complete the **From and To dates** in Activity section:  

 - In **Active from** field set the first date the reward is available. You can either enter the date or select it from the calendar
 - In **Active to** field set the last date the reward is available. You can either enter the date or select it from the calendar
 - If you want the reward to be active all the time mark **All time active** checkbox. When you choose that option *Active from and Active to fields will not be available*.
 
.. image:: /userguide/_images/reward_activity.png
   :alt:   Activity

.. note:: 

    **Active to** and **Active from** fields are available only when reward activity (availability) is limited

.. note:: 

    Status of the Reward campaign (Active/Inactive) has higher priority than time boundaries from Active section.
    
    Even if time boundaries from Activity section are valid, changing Status to Inactive means that reward will not be available to customers.


13. If applicable, in **Campaign photo** section upload reward images that will be visible on the storefront

 - To **add** a photo tap ``Upload`` to import main image
 - To **add** more images click ``Add photo`` and then upload another photo. Reapeat it for all photos that you want add.
 - To **remove** a photo click remove |remove_photo| icon near by particular field (during *creation*)

   .. |remove_photo| image:: /userguide/_images/photo_remove_icon.PNG

 - To **remove** images after creation click bin |bin| icon in the photo upper right corner (in *edit mode*)

   .. |bin| image:: /userguide/_images/bin.png

 All added images will be visible in **Campaign photos** field after *save*

.. image:: /userguide/_images/reward_photo.png
   :alt:   Reward photo

.. note:: 

    Image size is limited to 2MB. Image dimensions could not be smaller than 600 x 600 px. Allowed file formats: png, gif, jpg.


14. When it is done, tap ``SAVE``  
