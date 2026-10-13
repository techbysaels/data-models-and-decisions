# NAuto Case

Nauto connects AI-based detection to a clear operational response: alerting a distracted driver and giving a supervisor information for follow-up. The case examines how that connection can improve fleet safety and reduce accident and liability costs.

## Background

Nauto is an AI-enabled driver and fleet safety platform. Its cameras and other sensors monitor driving conditions and behaviour so the system can identify risk, warn drivers, and notify their supervisors. The aim is to help prevent incidents while also providing evidence for reviewing those that occur.

## What is the rationale for what they are trying to do?

Nauto wants to improve fleet safety by predicting and preventing driving incidents before they occur instead of reviewing events after they happen. They want to warn drivers while there is still time to respond; however, this comes with challenges because processing videos to provide a prediction is not an easy task. To address it, they have come up with a hybrid solution, where edge processing is key to prevent incidents and cloud processing is best to test and refine models before deploying improved versions to the vehicles.

Taking that into account, this solution is clearly tied to an specific business purpose: improve safety and reduce financial consequences of driving incidents. For example, for a commercial fleet, fewer accidents can mean lower repair costs, less vehicle downtime, and reduced liability costs.

## What are the AI elements, and what are they supposed to do?

Camera sensors and image-processing algorithms help identify where the driver is looking and whether their attention has moved away from the road. Vehicle signals, including braking and movement, provide additional context. Combining those observations allows the system to detect risky situations and raise progressive alerts.

They also use on-device AI models to analyse driver behaviour, traffic elements, movement, and contextual information in real time to detect potential distractions and risk behaviours and raise progressive alerts to the drivers. They also use CNN models that are tested and refined in the cloud and will later be deployed remotely to the monitored vehicle. Multi-sensor data fusion and predictive risk scoring are located in their platform to help supervisors identify patterns associated with future collisions. They have also developed their own deep-learning model for incident detection named CrashNet, which is trained on real-world incidents to separate valid collisions (even lower-impact ones) from invalid ones; then, this information is used to differentiate right claims from dubious ones.

## What data is needed, and how is it acquired?

The data needed to power these AI solutions are driver-behaviour data, traffic information, vehicle movement, video, contextual data, sensor data (location, speed), trip context, and environmental context. This data is acquired through the devices located in the vehicles to monitor and is processed locally when immediate action is required. They also store and process large volumes of data in the cloud to test and refine their models, which will then be updated to the devices. Finally, videos are also uploaded to the platform only when incidents occur or the supervisor has requested it intentionally; with this, the platform will not depend on uploading the complete video, but on the video that was recorded when the incident happened.

## What is the interface with humans? What is the interface with expert operators?

Drivers interact with the system through real-time alerts and a coaching interface, because when the system detects a distraction or a risky behaviour, it raises progressive alerts that will tell the driver to correct their behaviour immediately. The warnings need to be clear enough for the drivers to understand them and the system should consider that repeated inaccurate alerts will make a distraction itself.

On the other hand, fleet and safety managers or supervisors will receive notifications with video and contextual information on the platform, containing timelines, sensor data, location, speed, and driver behaviour to use as evidence for investigation, coaching, and claims handling. This separates the roles of the AI from the humans, because AI will be in charge of detecting and preventing incidents, while expert operators will use the results as evidence to improve safety and claim decisions.

## Conclusion

NAuto shows how sensors and AI algorithms can enable an intelligent process when the output leads to a defined human action. A distraction signal becomes a warning, and an event record becomes evidence for review. The business case depends on whether those actions improve safety and reduce accident and liability costs.

## Source
- [Nauto Product Overview (YouTube, 2020)](https://www.youtube.com/watch?v=MmRjOnbinjE)
- [AI Dash Cam Proven to Reduce Fleet Risk (Bruggeman, 2021)](https://empiricearth.com/insights/ai-dash-cam-proven-to-reduce-fleet-risk)
