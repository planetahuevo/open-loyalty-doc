.. index::
   single: sku

Bought specific SKU
===================

Segment of customers who bought specific products (on the basis of selected SKU).    

**For example**, you can create segment of customers who bought products of specific SKU "123ABC" or "X1Y8Z0"

.. tip::

    **SKUs can contain spaces or any other special characters, but remember that "SKU 123." is not equal to "sku 123."**



To create only Bought specific SKU type segment:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Tap **Segments** on the Admin sidebar and choose **Add segment**. You can also add rule directly from **All segments** list by clicking ``Add segment`` at the top of the page 

.. image:: /userguide/_images/add_segment_button.png
   :alt:   Add Segment Options  


2. In **Basic informations** section, do the following:  

 - Enter a unique segment **Name** to identify the customer segment when working in the Admin
 - Enter a brief **Description** that explain purpose of the segment for internal reference
 - To activate the customer segment, in **Active** field select "**Active**" from the dropdown list

   
.. image:: /userguide/_images/basic_segment.png
   :alt:   Basic Informations Section

3. In **Segment Parts** set the conditions that must be met to assign the customer to *only* **Bought specific SKU** segment.   

   During creation, you need to specify one or more **SKUs** that will be included. 

.. image:: /userguide/_images/segment_sku.png
   :alt:   Bought SKUs Type

.. note:: 

    One Segment consists of one or more conditions (types). Conditions can be combined through AND and OR logical operators.
    
     - **AND Condition** 
    
         is used to perform a logical conjuction on two conditions. Both conditions linked with this operator must be true. 
    
         **For example**, you can create segment with a list of customers who made purchase in specific POS and bought specific SKU. The list will contain customer who met both, 1st and 2nd condition.
     
     - **OR Condition** 
 
         is used to perform a logical disjunction on two conditions. At least one of conditions linked with this operator must be true. 
    
         **For example** you can create segment with a list of customers who made purchase in specific POS or bought specific SKU. List will contain customer who met only the 1st condition, who met only the 2nd condition and met both conditions.
  
To learn more about conditions type, see :doc:`Segment parts types </userguide/segments/creation/segment_type>`

4. You can simply **remove condition** by clicking **bin** icon |bin| in a particular row

.. |bin| image:: /userguide/_images/bin.png

5. When it is done, tap ``SAVE``  
