# Supply-Chain-Container-Analysis
Track and analysis shipment container behaviours


> Changi Express Logistic (CEL) is an international freight forwarder with a monthly container
volume of up to 50K containers globally via ocean, air and land. They pride themselves as one
of the leading freight forwarders that deliver On-Time and In-Full delivery to their customers.
More recently, CEL observed a sharp decline in carrier reliability schedules across all major
trade lanes which in turn affected their operations globally. The data that the CEL operators
receive from the carriers directly is often missing, is inaccurate or is only updated very late into
the journey/just a day before the arrival. That does not offer enough time for the CEL teams to
communicate the delay back to their own customers.

> Thus, CEL’s Innovations Team has sourced a handful of vendors (including Portcast) for testing
on how to improve existing Ocean Supply Chain Visibility. Portcast is now 4 weeks into the POC
for the predictive ETA solution. Nikana-San leads Innovations Projects and is our key
stakeholder within CEL. Our weekly 1-hour check-ins are typically used to clarify on predictions
being generated from our backend APIs/Emailed Reports for the cargo containers uploaded by
the customer on a daily basis at a predefined schedule. E.g. 5.00am daily, each batch of approx.
200 new cargo containers (Bill of Lading No.s or Booking No.s or Container No.s are used to
make a POST request on our API system) With 80% of the container volume allocated for the trial having arrived at the POD, you are now
working closely with the Account Manager to prepare for the next mid-trial review of the
performance so far.

## Goal of this Case Study:
The required outcome of the following exercise is to convert CELL from a Trial
Account/POC-Proof of Concept to a Paid account.

# Deliverable-1: Defining 3 key metrics to determine success of the trial
1. Based on the data provided, create 3 KPIs that we can use to evaluate the predictions provided
to the customer (Hint:The predictions are stored in the column portcast_predicted_pod_eta.
Every couple ( container, vessel leg ) has one and only actual arrival. You can give priority to
pod_ata column and fallback to container_pod_actual_discharge if pod_ata isn’t available )
Deliverable-2: Anomalies
1. Use Google Colab: Ipython Notebook to explore these by using pandas (Hint:
https://github.com/pandas-dev/pandas) for data exploration in the above dataset. (discovery of
anomalies in the dataset)

# 2. After identifying anomalies draw distribution graphs (Hint: https://github.com/plotly/plotly.py library
to draw your charts) to demonstrate data challenges you have encountered
3. Export CSV in the same folder where you have Google Colab. (Hint:Only anomalies CSV(s) from
the above Google Colab notebook)

# Deliverable-3: Customer Current Performance
1. Showcasing existing visibility supply chain performance of the customer

# Deliverable-4: Portcast Performance
1. Performance improvement from using Portcast predictions

# Deliverable-5: Insightfulness Test
1. Define 3 most Imp Questions based on sampling the data manually/programmatically to evaluate
what 3 questions your customer might ask in the next call.
