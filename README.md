# Sarasmarg---Smart-India-Hackathon-22
Winner Project of Smart India Hackathon'22
# 
#
BAD ROADS, IN A NUTSHELL, Every year, crores and crores of budget are drained for pothole maintenance and death compensations, resulting in a huge loss of human resources, an adverse impact on fuel consumption, regular breakdown of vehicles, traffic congestion…

All these alarming facts and figures point towards the necessity of a viable, reliable, scalable, intelligent tracking system that would not only monitor the road’s health at an early stage but would also immediately trigger reports to concerned authorities for maintenance…” as a stitch in time saves nine”.

Having solved this complex problem, the Morse coders came up with a one-stop solution that involves the least manual work and is scalable, reliable, low cost, and works with an aim "AB HAR MARG SARASMARG".

Let's talk about how our solution works in detail.......

Our entire system is divided into two parts. The first part is detection, and the second is reporting, for which we have built an admin portal. We used two sources, one CCTV camera and another mobile application. Using the Cognitive Services of Microsoft Azure, our deep learning model is deployed to detect road conditions in frames of the video feed. Our CCTV camera stream is fetched at a fixed rate from our in-house Data Center and then processed in a remote server. We can detect potholes from the video feed by analyzing the frame and categorizing them into shallow and deep potholes. A real-time database stores data like camera location, Camera ID, image annotations, and date-time.To avoid repetitive reporting of the same issue through the CCTV system, that location's reporting will be temporarily disabled.

Similarly, Any user who finds potholes/road cracks can click the picture via the mobile app and report the issue. The clicked picture is then processed at the same remote server. Post-verification results like location, user id, severity, Image, date, and time are stored in the database. 
Administrators (Govt. officials, Maintenance Authority, Contractors) are notified via a web-based dashboard whenever a deformation of a road is detected, or when a complaint is registered, with the location well marked on the map so that action can be taken promptly.
The user app also has features like a feedback system and complaint tracking. Thus, the solution provides a single platform to bring the User, Admin, and other Stakeholders together as one unit.
We are also planning to use the inbuilt sensors of smartphones like accelerometers and gyroscopes for measuring the road's health.

OUR WEBSITE:
https://sarasmargindia.tech/
