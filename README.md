# Angel Eyes

[toc]

Angel Eyes is an IoT device that monitors a baby’s sleeping position and environment. Caregivers can view a live stream from anywhere and receive notifications if the device detects any issues.

> Inspired by https://www.microsoft.com/en-us/ai/ai-lab-angel-eyes



## The need
Accidental Suffocation and Strangulation in Bed (ASSB) is a prominent cause of death for newborns. Baby monitors could be smart enough to react to scenarios and data, and to proactively alert caregivers when a baby is at risk for ASSB.

## The idea
A smart baby monitor uses AI to track the infant and their surrounding conditions. The system is always on, continuously monitoring and alerting caregivers. The device is non-intrusive, monitoring externally without any physical restrictions.

## The solution
Angel Eyes uses Microsoft Azure, with a camera and sensors for temperature and humidity. When it detects risks like high room temperature, an object in the crib, or the baby’s unsafe position—it alerts the caregiver to take corrective action.

## Safer monitoring for newborns
Angel Eyes was created by parents who wanted to track their baby’s safety at all times, without losing sleep. Learn how Microsoft Azure’s cognitive and visual services plus IoT monitoring devices helps ensure their baby’s well-being.

# Technical details for Angel Eyes

Accidental Suffocation and Strangulation in Bed (ASSB) is a significant cause of infant mortality, with more than 85 percent of ASSB occurring from birth to six months of age. Infants with low birth weight have an increased risk of ABBS and SIDS. In 2016, 900 deaths in the US were reported and attributed to accidental suffocation and strangulation in bed. There is an immediate need to improve upon the classic baby monitors in order to make them smart enough to adapt to various situations, to react to various scenarios and data points, and to take appropriate corrective action.

Research identifies some key requirements for a smart monitoring system:

Always On: Continually watching over the baby and its surrounding conditions.
Proactive: Proactively notifying the caregiver if the surrounding conditions change.
Non-Intrusive: Externally observing the infant’s environment without poking and prodding, thereby allowing the infant the least restrictive environment.
Angel Eyes was created to ensure a safe and non-intrusive way of monitoring the infant that is leaps and bounds ahead of the on-market baby monitor cameras utilizing the recent advancements in Deep Learning. Angel Eyes is a non-intrusive, safe and efficient monitoring system, that proactively alerts the care givers as the environment or the infant position changes.

The key components of the system are powered by Microsoft Azure and a Raspberry PI device, a Pi-Camera, a DHT11 Temperature and Humidity Sensor and utilizing the Microsoft Azure stack to relay communications back to the caregiver. This method helps us solve for multiple use cases:

a. When the infant is sleeping on their back with no objects detected, a safe light is visible.
b. When Angel Eyes visually detects that the infant has moved to their side, or that an object is in the crib, it sends an alert to the caregiver.
c. When Angel Eyes environmental sensors detects that the room temperature is high, an alert is sent to the caregiver notifying them to take corrective action.
