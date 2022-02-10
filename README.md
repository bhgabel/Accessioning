# Paper Orders {#header}

1. Check ESI on block/slides to order and path report
	- Find in path report: name, DOB, gender, ESI, DOC, diagnosis
2. Duplicate patient search
	- First search: full name, <br>Second search: first three letters + * + year of birth
	- If order exists → go to **[Order Exists](#order-exists)**
	- If only patient exists → go to **[Contact Exists](#contact-exists)**
3. Create new contact [patient]
	- ![]("./images/image1.PNG)
	- ![]("./images/image2.PNG)
4. Order entry guide
	- Channel = paper, Triage = new, bill type = per order, description = AT `initials`
5. Create necessary Order Roles
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

### Order Exists {#order-exists}

### Contact Exists {#contact-exists}
