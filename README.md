# Paper Orders

1. Check ESI on block/slides to order and path report
	- Find in path report: name, DOB, gender, ESI, DOC, diagnosis
2. Duplicate patient search
	- First search: full name, <br>Second search: first three letters + * + year of birth
	- If order exists → go to **[Order Exists](#order-exists)**
	- If only patient exists → go to **[Contact Exists](#contact-exists)**
3. Create new contact [patient]<br>
	![](./images/image1.PNG)
	![](./images/image2.PNG) ``TODO edit image in ms paint``
4. Order entry guide
	- Channel = paper, Triage = new, bill type = per order, description = AT `initials`
5. Create necessary Order Roles<br>
	![](./images/image4.PNG)
	- **Ordering**: find approved account via *CR#*, hospital name, address, or fax<br>Need approved contact (oncologist)
	- **Specimen Submitting**: find approved account via same method<br>Need approved contact (pathologist)<br>If not provided on order form → same as Ordering
	- **Material Return**: only required if different account from Specimen Submitting<br>Priority for location: given on order, specific paper provided, 2/3's rule (match between specimen submitting, air bill, and path report)
	- Check each account for notes
6. Edit each Order role
	- Select appropriate address affiliation, ensure phone and fax match order form
7. Create Specimen Arrival Case
	- Required data: tracking number, specimen receiving [specimen submitting], material return
8. Edit Order Line Item (named type of test)
	- ICD code defaults: female = C50.919, male = C50.929
		- Not required for Bill Account
	- Submitting diagnosis
	- ER status, Node status
9. Edit order details
	- Signature date, multiple primaries, MRN
10. Order Intake Complete, LIMS Accessioning
11. Enter data into LIMS
	- ESI, tracking number, number of stuff [blocks/slides], container code, DOC

### Order Exists

1. Go to Order Intake dropdown
	- Enter OR number and tracking number
2. Process Case [Specimen Arrival]
	- Need tracking number, primary customer, and material return
	- Can select material return from dropdown<br>![](./images/image5.PNG)
3. Ensure there are other no open cases
4. LIMS Accessioning
	- ESI, tracking number, number of stuff [blocks/slides], container code, DOC

### Contact Exists

1. Check and enter any missing patient information
2. Order Entry Guide
	- Channel = paper, Triage = new, bill type = per order, description = AT `initials`
3. Go to Electronic Documents
	- Check that all information matches with appropriate patient
	- Re-index<br>select Specimen Related Materials from document type dropdown<br>enter order number<br>![](./images/image3.PNG)
4. Continue from Step 5 above [return to top](#paper-orders)

### Missing Data Cases
