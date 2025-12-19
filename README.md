# Ex09 Event Registration Web Application
## Date:19.12.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
import React from "react";
import screenshot202512191331021 from "./screenshot-2025-12-19-133102-1.png";

export const Image = () => {
  return (
    <div className="w-[1372px] h-[916px]">
      <img
        className="fixed top-0 left-[325px] w-[412px] h-[916px] aspect-[1.5] object-cover"
        alt="Screenshot"
        src={screenshot202512191331021}
      />
    </div>
  );
};
import React from "react";
import screenshot202512191342351 from "./screenshot-2025-12-19-134235-1.png";
import star2 from "./star-2.svg";
import star4 from "./star-4.svg";
import star5 from "./star-5.svg";
import star6 from "./star-6.svg";
import star8 from "./star-8.svg";
import star10 from "./star-10.svg";

export const AndroidCompact = () => {
  return (
    <div className="bg-white w-full min-w-[409px] min-h-[909px] relative">
      <img
        className="absolute top-[417px] left-[17px] w-5 h-[25px]"
        alt="Star"
        src={star8}
      />

      <img
        className="top-[232px] absolute left-[17px] w-5 h-[25px]"
        alt="Star"
        src={star2}
      />

      <img
        className="top-[321px] absolute left-[17px] w-5 h-[25px]"
        alt="Star"
        src={star4}
      />

      <img
        className="top-[369px] absolute left-[17px] w-5 h-[25px]"
        alt="Star"
        src={star5}
      />

      <img
        className="absolute top-[417px] left-[17px] w-5 h-[25px]"
        alt="Star"
        src={star6}
      />

      <img
        className="top-[506px] absolute left-[17px] w-5 h-[25px]"
        alt="Star"
        src={star10}
      />

      <img
        className="absolute top-0 left-0 w-[409px] h-[909px] aspect-[0.53]"
        alt="Screenshot"
        src={screenshot202512191342351}
      />

      <div className="absolute top-[99px] left-[37px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-white text-[40px] tracking-[0] leading-[normal] whitespace-nowrap">
        EVENTS
      </div>

      <div className="absolute top-[260px] left-[27px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-white text-2xl tracking-[0] leading-[normal]">
        NETWORKING OPPORTUNITES
      </div>

      <div className="absolute top-[338px] left-7 [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-white text-2xl tracking-[0] leading-[normal]">
        INDUSTRY EXPOSURE
      </div>

      <div className="absolute top-[422px] left-4 [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-white text-2xl tracking-[0] leading-[normal]">
        MENTORSHIP AND SUPPORT
      </div>

      <div className="absolute top-[496px] left-7 [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-white text-2xl tracking-[0] leading-[normal]">
        HANDS ON WORKSHOP
      </div>

      <div className="absolute top-[579px] left-[27px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-white text-2xl tracking-[0] leading-[normal]">
        CASH PRICES
      </div>

      <div className="absolute top-[663px] left-[37px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-white text-2xl tracking-[0] leading-[normal]">
        CERTIFICATE
      </div>
    </div>
  );
};
import React from "react";
import screenshot202512191357081 from "./screenshot-2025-12-19-135708-1.png";

export const Image = () => {
  return (
    <div className="w-[880px] h-[1073px]">
      <img
        className="fixed top-[132px] left-[233px] w-[414px] h-[888px] aspect-[0.82]"
        alt="Screenshot"
        src={screenshot202512191357081}
      />
    </div>
  );
};
import React from "react";
import screenshot202512172047113 from "./screenshot-2025-12-17-204711-3.png";

export const AndroidCompact = () => {
  return (
    <div className="bg-[#ea0f0f] w-full min-w-[422px] min-h-[905px] flex flex-col">
      <img
        className="w-[422px] h-[87px] mt-12 aspect-[5.01] object-cover"
        alt="Screenshot"
        src={screenshot202512172047113}
      />

      <div className="ml-[88px] w-[218px] h-[37px] mt-[158px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-white text-4xl tracking-[0] leading-[normal] whitespace-nowrap">
        THANK YOU
      </div>

      <p className="ml-[55px] w-[352px] h-24 mt-14 [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-white text-xl tracking-[0] leading-[normal]">
        WE ALL ARE EAGERLY WAITING
        <br />
        FOR YOUR PARTICIPATION IN
        <br />
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; THE CODING MARATHON
      </p>

      <div className="ml-[148px] w-[97px] h-6 mt-[267px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal] whitespace-nowrap">
        CONTACT
      </div>

      <div className="ml-[43px] w-[336px] h-6 mt-[15px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal] whitespace-nowrap">
        EMAIL: saveethaengclg@gmail.com
      </div>

      <div className="ml-[76px] w-[210px] h-12 mt-[15px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-xl tracking-[0] leading-[normal]">
        PHONE : 9057324567
        <br />
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8762489213
      </div>
    </div>
  );
};
```


## OUTPUT:
![alt text](<Screenshot 2025-12-19 141824.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
