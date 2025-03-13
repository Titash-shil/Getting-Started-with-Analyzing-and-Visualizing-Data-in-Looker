#  || [Getting Started with Analyzing and Visualizing Data in Looker](https://www.cloudskillsboost.google/focuses/25305?parent=catalog) || 

## # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

---
## ⚠️ **Disclaimer:**
#### This script and guide are provided for educational purposes to help you understand the lab process. Please ensure you understand the steps before using any scripts. Before using the script, I encourage you to open and review it to understand each step.The goal is to help you learn how to complete the labs effectively while following Qwiklabs' terms of service and YouTube's community guidelines.
---

- # Follow the all steps mentioned bellow to complete the lab : ⬇⬇

 - ###  First, on the bottom left of the Looker User Interface, click the toggle button to enter `Development mode`.
 - ### Click the Develop tab and then select the qwiklabs-flights.
 - ### Open faa.model file and paste the below code one by one task wise.

- ### TASK 1 :
```

# Place in `faa` model
explore: +airports { 
    query: qwiklab_explorers_task-1 {
      measures: [average_elevation]
    }
  }
```
- ### TASK 2 :
```
# Place in `faa` model
explore: +airports {
    query: qwiklab_explorers_task-2 {
      dimensions: [facility_type]
      measures: [average_elevation, count]
  }
}
```
- ### TASK 3 :
```
# Place in `faa` model
explore: +flights {
    query: qwiklab_explorers_task-3 {
      dimensions: [depart_week]
      measures: [cancelled_count]
      filters: [flights.depart_date: "2004"]
  }
}
```
- ### TASK 4 :
```
# Place in `faa` model
explore: +flights {
    query: qwiklab_explorers_task-4 {
      dimensions: [depart_week, distance_tiered]
      measures: [count]
      filters: [flights.depart_date: "2003"]
  }
}
```

---

## Congratulations ..!!🎉  You completed the lab shortly..😃💯

## *Well done..!* 👏

## Thank you for visiting.... :) 🗯️

## [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)

## Join to our community [Digital Dominators](https://chat.whatsapp.com/J0o1beFGCHfJ8ZHGKjcqkd)
