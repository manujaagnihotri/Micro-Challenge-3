Micro Challenge 3   
By Flora, Manuja and Dhrishya   

Creating a Soil Button and triggering a visual by completing the circuit through the body. -
-

The Idea - 
The deliverable requirement for the last micro-challenge was to create an interactive digital or physcial visual that uses the body as an input.

We initially began the process with ideating on different ways to incorporate a soil button and making the body a part of it. We first thought of collecting different soil samples from around Barcelona, once stepped on a specific soil sample, a visual would be triggered that showed the location and the quality of soil. However, we realised we were not playing around with the concept of the body and making it as interactive as possible. After a lot of different discussions with faculty members and within each other, we finalised on the idea of using the body to complete the circuit, and through the electrical conductivity that passes within the body when stepped on soil barefoot, a speculative visual would be triggered.We also experimented with a DIY heart rate sensor to potentially add to the interactive process, however we were unable to link it to the narrative and tried to keep it as simple as possible. Below you can see the images of some experiments we did with different sensors to shortlist and finalise the idea eventually.

![Test 1 1](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/90f33070-3ca2-46e8-94fd-b0e6f1196b2b)
This was a test we tried out with velostat material and the soil button - the basic idea was to check if we could connect the two and we could!

![Test 1 2](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/1ca28ead-0132-4038-8559-18befbf8446b)
Here you can see the readings on Arduino that we were able to recieve from adding pressure to the Velostat and touching the soill button.

![Test 1 3](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/b5a33343-c4f6-460a-a8b8-2be59bdd43ff)
Here is a closer image to see how it worked!

![Heart Rate Sensor 2](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/e8e78326-caa0-497f-b0fb-2efbb9ce41b5)
This is the heart rate sensor we created using a red LED bulb and photovoltic sensor. When a finger was inserted inbetween the two - it would measure the flow in blood to give the reading of the rate of heart. 

![Heart Rate Sensor 1](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/949a0505-2179-4810-afc5-8297f40f05f0)
We loved this idea, however incorporating this into the final was getting slightly chaotic and we wanted to simplify things a little.


Final Idea - Once stepped barefoot on the soil button, the circuit is closed through the conductivity flow within the body. The closing of this circuit triggers a speculative visual that is then shown digitally on a screen.

The first step in order to achieve that was to recieve different readings from the soil button when the circuit is completed from human touch. 

![Test 1 Arduino Reading](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/04e02f45-4aef-44be-82fd-24014e542b21)

Here is an image of the Arduino reading that we recieved from a soil sensor that read - temperature, electrical conductivity and water content. Recieving this data was enough for us to create a visual from it that altered the aesthetic of it.

![Test 1 Arduino Reading 2](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/3efded54-4088-43cb-84ff-bc82528d7ef4)

Here is a look at how the connections worked within each other to recieve data from the soil on Arduino.

Once we figured out how the connections worked within each other, we created a quick mockup prototype of how the soil box would look like, to check if it was still functioning correctly.

![Prototype 1 1](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/f1a79537-3ec6-4456-bb38-a5fe8724cb7f)
Once the soil sensed the electrical conductivity within the body, we were able to get readings from the soil sensor on Arduino.

Now that we were recieving data, the next step was to create a visual that would be activated once stepped on soil barefoot. Below you can see the images of the visuals we created.

![VIsual 1](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/6f93d531-44ca-4bf1-ab2d-44708ac040a8)
![Visual 2](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/98210790-e297-475b-b644-af68611731db)
![Visual 2 1](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/24b95c60-59ce-4969-9a8d-0002437ccd15)
![Visual 2 with arduino reading](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/f89beb38-459a-4ab0-8265-d0abff884ac4)
This is the visual with the live reading of the soil sensor from Arduino.

![Connection soil to visual 1](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/608c036d-8f54-454a-bd1e-ba4fcab34465)
This is us testing out the visual and how it interacts within the soil button once the circuit is closed.

Here is the Arduino Code for the soil button sensor 

![Code 1](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/c8d58438-5cdd-4cd4-b07e-b96237469273)
![Code 2](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/709bedc9-62b0-445f-b109-7838be68da65)
![Code 3](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/0d144748-db0c-4778-bca1-7f5cf482cd93)
![Code 4](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/04442824-cd3c-492e-9ea8-0713073adaf3)
![Code 5](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/530f2542-6213-42c2-9d3b-4cdeba28f68b)

For the final day during the presentation, we had to use the first visual as it was less complex than the second one and as we are beginners to touchdesigner, it was faster. We had one of our classmate step on the soil barefoot to complete the circuit, and once she did, the visual was triggered as we had hoped (after lots of trials and errors). We then tried a fun experiment where we all joined hands to increase the electrical conductivity within the human bodies to see if the visual on touchdesigner would get bigger and it did!! Below are the images of our final presentation!

![MDEF circle 1](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/b7440c3b-4158-4300-8ff5-0ba4452b5efd)
![MDEF circle 2](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/478541a9-cdd8-498f-ac05-67c27bf3711c)
![MDEF circle 3](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/73d76364-4684-4484-879e-2df34310d766)
![MDEF circle 4](https://github.com/manujaagnihotri/Micro-Challenge-3/assets/147051463/9b366512-8d37-437e-89f7-e8665caede02)

The Future
We want to have different soils activate different visuals
We want to have the visuals be activated with different feet
We want to use the different soil sensor readings to activate different things in the visual
We want to have the visual have a more dramatic change when a big group all connects with each other and make it more fun and interactive

Our Learnings 
We learned how intricate the micro-bacterial and human-bacterial intelligence can be
We learned the very basics of touchdesigner and connecting it to arduino 
We learned how to make the project more self-explanatory rather than having to present to explain
We learned how to incorporate the body and make our projects more interactive and fun

