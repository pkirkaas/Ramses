**RAMSES
****I**

**Relief
Aid Management System for Emergency Shipments**

## Introduction:

### Overview:

This
program keeps track of shipments of commodities as they are brought
into the country, stored, and disbursed through distribution centers
around the country.

The
basic unit of input is the waybill, of which there are two classes:

1. **Incoming Shipments:**  These record the importation of food
	shipments into the country from the most proximate port of lading. 
	Keeping track of this information tells you how much food from
	different donors you have brought into the country and, combined
	with the data from internal distribution, below, tells you how much
	food you should have left undistributed in your warehouses at any
	given time. 
2. **Internal Distribution:**  This is the shipping record/waybill
	(also called Authority to Collect, or ATC) of shipments from the
	local storehouse (called an EDP) to the local Distribution Center,
	where the food is actually disbursed to the hungry.  Keeping track
	of this information tells you how much you have distributed to the
	people -- in total, by region, by district, by month, by year to
	date, by Donor, by SI, etc.  In addition, this module has an
	automatic billing / charge calculation component.  It calculates the
	expected transport charges based on the tonnage and distances.  This
	can be used to verify the bills issued by the transporters, and
	calculate transport charges by area, SI, period, etc, or any
	combination thereof. 

Each
of these datasets can be recorded and reported on separately and
independently of each other, but together they combine
synergistically to give a much better overall picture; for instance,
to estimate how much food you have left in a warehouse, you have to
know how much has come in and how much has gone out.

### Motivation:

There
are several other commodity tracking programs available -- why
another?  Let’s face facts -- some of these other systems can be
difficult to interfais with.  Workers (and even managers) in the
development community occasionally have more important issues to
struggle with than computer literacy.  DOS based packages, while
potentially sophisticated, have not been noted for ease of use.  The
guiding principle behind every phase of Ramses
development has been ease and clarity of use.  This has of course
been a goal in other systems, but Ramses
benefits from the advantage of being developed in the Microsoft
Windows environment, which is structurally more user friendly than
DOS.

Because
Ramses
uses the latest software development tools, the development cycle is
much faster.  This means that new features can be added quickly and
cheaply, allowing for quick customization for specialized needs.  For
example, this version of Ramses
was developed in three months for a cost of less than US$6000 (not
counting the time, effort and costliness of management).  This makes
customization possible in locations around the world which have been
unable to use existing standard packages because of unique local
conditions, but have heretofore been unable to afford the standard
costs of customized programs, which typically cost tens to hundreds
of thousands of dollars and take a year or more to develop.

Ramses
also attempts to provide a bigger picture by combining low level
distribution data with large scale grain movements to track the grain
from foreign port to needy recipient.

### Features:

If
data is entered correctly (the greatest vulnerability of the system)
Ramses
can report:

- 
	How much relief food was picked up, distributed, lost, or damaged
	throughout the country by Distribution Center, EPA, District, EDP
	and/or SI Number; for any given month or range of months. 
- 
	Calculate expected transporter charges by individual shipment,
	center, EPA, district and EDP totals for a given month or range of
	months for verification of transporter billing. 
- 
	Compare all transporters used in a given period to report on total
	mileages, charges, tonnages carried and lost, and percentage of load
	lost or damaged for each transporter.  Can be used to identify
	patterns if some transporters have consistently high losses, etc. 
- 
	Compare food targeting (in Metric Tons) with actual deliveries for
	any month or range of months by EPA, District and EDP. 
- 
	How many tons were delivered _to_ each EDP, how many tons were
	distributed _from_ each EDP, and thus how many tons should be
	remaining at each EDP (by SI or in aggregate), for any selected
	period. 
- 
	Trace SI commitments from foreign ports of loading to domestic
	EDP’s, districts, and EPA’s.  For each SI, report the total
	commitment amount; the amount of initial commitment which has been
	collected from the external ports and delivered to the EDP’s, the
	amount of that which has been actually disbursed at the distribution
	centers, and the balance of the committed amount not yet delivered
	to the EDP’s. 

##### Future Directions:

This
version of Ramses
provides a framework of basic services for essential reporting.  Some
future goals include:

###### Drill Down:

(Greater
detail and analysis in-country)

- 
	Transport Cost Projections:  With the data already collected for
	Targeting and Distribution Centers, it will be possible to estimate
	transport costs for any period (month, quarter, total emergency
	duration), by district, region, SI, etc. 
- 
	Beneficiary Reporting:  Again, with the data already collected,
	Ramses
	II will report on number of beneficiaries expected, number reached,
	average distribution per beneficiary, by district, region, month,
	etc. 
- 
	Distribution / Delivery Comparisons:  Food that gets delivered to
	centers but not distributed to recipients is a big problem.  Ramses
	II will identify and report those centers which have the greatest
	problems. 
- 
	Food Budget Projections:  Project total grain requirements or by
	district or EPA for any given month, period, or duration of entire
	relief project. 
- 
	Collect data directly from the transporter on uplift information. 
	Ramses
	now collects data only when shipments have been received at the
	district and the completed waybill has been forwarded to TLU. 
	Consequently, the data is typically weeks or months old, and there
	is no way to identify shipments which have been loaded and sent out
	from the warehouse but not received, or waybills that have been
	lost.  The transport broker typically collects the essential uplift
	information every day on a primitive dBase or spreadsheet system. 
	Ideally, this data should be provided on disk by the transport
	broker and loaded automatically into Ramses
	II to provide up to the minute sit reps
	(situation reports) and to help track shipments which have gone
	astray. 
- 
	Food for Work:  Food Accounting Module -- Collect data on food for
	work projects, participants, beneficiaries; HSD’s (Homo Sapiens
	Days) of work projected, performed, paid, etc. 

###### Blow Up:

(Bigger Picture)

- 
	Track the shipments and commitments farther back to the source. 
	This information is generally available, but occasionally not well
	co-ordinated.  In those rare instances when a donor expresses
	interest in the disposition and status of its donation,
	incorporating this data into Ramses
	II will allow WFP to print up a quick but
	complete status report while the donor waits on hold from, say, an
	unnamed capital of the world’s remaining superpower. 
- 
	Combining the large and small pictures, Ramses
	II will use future shipping schedules with the Targeting Projections
	to plan shipments, reduce storage costs and spoilage, and monitor
	grain reserves compared with projected arrivals and requirements.
