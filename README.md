# ShambaPulse
# Contents

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
- [Judging criteria](#judging-criteria)
- [Featured software products](#Featured-software-products)
- [Github repository](#github-repository)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [Demo videos](#demo-videos)
  - [Demo links] (#demo-links)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)


## Project summary
ShambaPulse is a Food Security innovation platform based in Nakuru County, Kenya, designed to strengthen agricultural value chains through technology-enabled services. The project addresses key bottlenecks affecting farmers, buyers, financial institutions, and regulators by offering three integrated services:

Quality Assurance-as-a-Service (QAaaS)

Transport-as-a-Service (TaaS)

Investment-as-a-Service (IaaS)

ShambaPulse leverages Microsoft technologies such as Power Apps and Power Automate as well as IBM Technologies such as WatsonX and Cognos Analytics, combined with SMS-based communication systems, to ensure inclusivity, even for farmers using feature phones.


### The issue we are hoping to solve
ShambaPulse strengthens food security by:

Reducing post-harvest losses

Improving food safety compliance

Lowering transport costs

Enhancing farmer bankability

Increasing market trust

Digitizing agricultural logistics

By integrating quality intelligence, logistics optimization, and financial enablement, ShambaPulse transforms agriculture from subsistence-based activity into a data-driven, bankable, and scalable ecosystem.

### How our technology solution can help
1. Quality Assurance-as-a-Service (QAaaS)

ShambaPulse enhances food safety and quality verification for agricultural produce supplied to hotels, institutions, and government agencies.

 How it works

Agricultural produce is tested using food testing strips.

Testing can be conducted using:

Liquid solutions

Solid powder methods

Results are recorded in Excel sheets.

Through Microsoft Power Apps, results are:

Summarized automatically

Converted from technical language into simple English

Compressed to fewer than 459 characters (maximum SMS length)

Translated into vernacular language

Sent via SMS to feature phones

This ensures accessibility, simplicity, and transparency.

 Value Delivered

Assures hotels of food safety compliance

Improves farmer credibility

Reduces rejection rates of produce

Enables traceability and documentation

 Strategic Partnerships (QAaaS)

Collaboration with 3M to enhance the food strip prototype using their manufacturing expertise.

Licensing food strip technology to Kenya Bureau of Standards (B2G model).

## Technical description
The Arduino-based food quality testing system follows a structured sequential process beginning with sample preparation, where a food sample such as milk, meat extract, or juice is diluted with distilled water to produce a liquid test extract. The extract is then applied to chemical test strips and sensors including glucose enzyme strip, pH probe, ammonia sensor, and conductivity electrodes, where chemical reactions occur—producing measurable changes such as electrical current, voltage variation, gas concentration, or color change. These changes are converted into analog electrical signals, which are transmitted through the breadboard, serving as the circuit integration and prototyping platform that electrically connects the sensors, resistors, Arduino, and communication module without permanent soldering. The breadboard distributes power reanging to 5V , organizes wiring, and enables rapid testing and modification of the system design.

The signals are then sent to the Arduino for analog-to-digital conversion (ADC) and calibration using predefined mathematical formulas. The Arduino applies programmed decision logic to classify the food as SAFE, WARNING, or UNSAFE based on established threshold values. Finally, the processed results are transmitted wirelessly via the HC-05 Bluetooth module to a smartphone application, where the data is displayed, logged, and can be exported for reporting, traceability, and quality assurance purposes.
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/7553c223-5d32-4762-8a36-f61d74a99b57" />




End user is Kenya Bureau of Standards or even hotels
Partnership with:

Kenya Association of Manufacturers

Kenya Development Corporation

Central Bank of Kenya

2.  Transport-as-a-Service (TaaS)

Transport inefficiencies significantly increase food waste and cost in Nakuru. ShambaPulse provides real-time traffic intelligence and optimized transport selection.

 Real-Time Traffic Data Model

Identify businesses and individuals along selected transport routes.

These participants send SMS updates indicating traffic status:

High

Medium

Low

Data is processed via Power Automate to create a logistics intelligence platform.

Buyers and sellers receive SMS updates with real-time traffic conditions.
Fuel Consideration

Petrol vehicles cost more than diesel.

Fuel optimization reduces overall logistics cost.

 Strategic Partnerships (TaaS)

Fuel discount collaboration with Rubis Energy Kenya.

Bulk SMS partnership with Safaricom.

Licensing real-time traffic data to buyers and sellers.

3.  Investment-as-a-Service (IaaS)

ShambaPulse integrates quality verification and logistics performance data to create financial credibility profiles for farmers.

 How It Works

Aggregates data from QAaaS and TaaS.

Assesses:

Profitability

Sales performance

Liquid capital flow

Shares structured performance reports with partner banks.

Enables farmers to qualify for:

Loans

Grants

Impact investments

 Financial Partnerships

Collaboration with Equity Bank

Working with the payment department to assess farmer-to-buyer transaction flows, especially cash-preferred farmers.

Collaboration with Standard Chartered Kenya

Engaging the CSR department to promote inclusive finance.


### Our idea
Quality Assurance-As-A-Service involves testing quality of agricultural produce by use of food strips, the testing is done by wither use of liquid solutions or solid powder. The results are sent in the form of Excel Sheets and by use of Power Apps from Microsoft a report is summarized and can be sent to a feature phone that ensures that the number of text is less than 459 letters (which is the maximum that can be sent) and that technical text is converted into simple English and is later translated into vernacular language.




Transport-As-A-Service involves gathering real time data of traffic to save on cost of fuel wasted in long traffic and time for reducing the time the farm produce from the farmer reaches the buyer. By use of SMS both buyers and sellers can get real time data of the current status of traffic. Their are various transport options including trucks, pickups ( double cabin), pickups (single cabin), van, personal, saloon car, motorbikes and even bicycles. Every transport option has their own unique advantage and disadvantage. For trucks, they have a high transporting capacity but have high cost and they are slow in terms of speed and most of all cnsume a lot of fuel. Transport options for pickups ( double cabin) has a higher carrying capacity than pickups (single cabin). Vans have a higher carrying capacity than saloon cars.Motobikes have the advantage of avoiding long traffic but have a small carrying capacity than the others. Bicycles have the advantage of not consuming fuel thus they are cheaper but have the lowest carrying capacity. For transport options there are vehicles that use petrol and others use diesel. A transport option of petrol will cost more than that of diesel. The data for acquiring real time data of transport traffic is obtained by first determining businesses or people that are located on the route that is selected then they can use there phones to send an SMS of the current status of traffic indicating whether it is High, Medium or Low. This data would enable both buyers and sellers to determine the best transport option so as to save on time and cost. 


ShambaPulse is using Microsoft services such as Power Automate to create a logistic platform For Investment-As-A-Service, this involves working with banks to enable farmers to get access to finance based on the performance of their business with regard to profit and liquid capital.

## Technology implementation
1. Quality Assurance-As-A-Service (Entry Point)

This is the starting engine of ShambaPulse. Every farmer interaction begins here.

Technical Flow

Produce is tested using food strips (liquid or powder reagents)

Results are captured digitally by field agents

Raw test data is structured into standardized records

Results are simplified into SMS-ready language

Reports are delivered to farmers and buyers

The goal is to convert physical agricultural quality into digital trust data.

Software Layer

Powered by Microsoft Power Automate

Power Automate handles:

Automated lab result processing

Technical → simple English translation

Vernacular SMS conversion

Character compression (<459 limit)

Regulatory record archiving

Buyer notification triggers

This creates a real-time compliance pipeline.

Output of Stage 1

Certified produce records

Timestamped quality logs

Buyer trust signals

Regulatory-ready data

Digital identity of farm output

This dataset becomes the foundation for transport and finance decisions.

2. Transport-As-A-Service (Operational Layer)

Once produce is certified, the system moves to logistics optimization.

Technical Flow

Traffic status is crowdsourced via SMS

Reports are aggregated in real time

Route efficiency is calculated

Best transport mode is recommended

Buyers receive delivery ETA updates

The objective is to reduce spoilage, fuel waste, and delivery time.

Software Layer

Built using Microsoft Power Apps

Power Apps provides:

Transport routing dashboard

Traffic reporting console

Farmer logistics interface

Buyer tracking portal

Vehicle selection engine

Fuel efficiency comparisons

This layer turns static transport into adaptive logistics.

Output of Stage 2

Delivery performance records

Cost efficiency metrics

Speed-to-market data

Reliability scoring

Transaction timestamps

These logistics records strengthen financial credibility.

3. Investment-As-A-Service (Financial Layer)

This is the final stage, where operational performance becomes financial opportunity.

Technical Flow

Quality data + transport data are merged

Farmer performance trends are analyzed

Revenue stability is modeled

Risk scores are generated

Banks receive credit intelligence profiles

This converts agricultural activity into bank-readable metrics.

Software Layer

Driven by IBM Cognos Analytics

IBM Cognos provides:

Financial performance modeling

Predictive profitability analysis

Creditworthiness scoring

Investment dashboards

Bank-ready reporting

Policy compliance analytics

This is where ShambaPulse becomes a financial intelligence platform.

Output of Stage 3

Farmer credit profiles

Investment eligibility scores

Grant readiness indicators

Lending dashboards

Economic impact metrics

Farmers move from invisible cash operators → measurable financial entities.


## Judging criteria 


<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/39cc8b37-f9e8-45b2-8c84-55f315c48640" />


<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/d9013cfa-3a28-45f1-a4dd-2990e8af2af2" />

<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/6debcf0c-9928-4f6c-8e93-cf4e2b924a31" />

<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/73d14aa0-7f3e-462c-bbf9-8c28a9b98d40" />

<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/3d9f4a6c-544c-4a11-80ee-bab30529c547" />

For Qulaity Assurance he novelty of this project lies in its integration of low-cost microcontroller technology (Arduino), disposable chemical test strips, and wireless Bluetooth communication into a single portable food quality testing platform. Unlike traditional systems such as laboratory-based food testing kits or single-parameter devices like glucometers, this solution combines multi-parameter detection (pH, glucose, ammonia, conductivity) with real-time digital analysis and mobile reporting.

Additionally, the project introduces a hybrid detection approach—merging electrochemical sensing (like medical glucose meters) with colorimetric and gas-based food spoilage indicators—within a customizable and scalable architecture. By leveraging a reusable hardware core with locally producible consumable strips, it creates an affordable, field-deployable system suitable for SMEs, hotels, cooperatives, and emerging markets.

In essence, the innovation is not just in testing food quality, but in transforming it into a smart, connected, and scalable Quality Assurance-as-a-Service (QAaaS) model.

## Featured software products

Microsoft services such as Power Apps and Power Automate
IBM services such as WatsonX and Cognos Analytics



  
## Github repository
import { Link } from "react-router";
import { Sprout, Truck, ShoppingCart, TrendingUp, Smartphone, MessageSquare, Users, Package, TrendingDown, Upload, FileCheck, Shield, CheckCircle2, DollarSign, AlertTriangle, FileSpreadsheet, TrendingUp as Investment } from "lucide-react";
import { Card, CardContent, CardDescription, CardHeader, CardTitle } from "@/app/components/ui/card";
import { Button } from "@/app/components/ui/button";
import { useState } from "react";
import { Label } from "@/app/components/ui/label";
import { Input } from "@/app/components/ui/input";
import { Alert, AlertDescription } from "@/app/components/ui/alert";
import { Badge } from "@/app/components/ui/badge";

export default function HomePage() {
  const [uploadedFiles, setUploadedFiles] = useState<File[]>([]);
  const [showUploadSuccess, setShowUploadSuccess] = useState(false);
  const [excelFiles, setExcelFiles] = useState<File[]>([]);
  const [showExcelSuccess, setShowExcelSuccess] = useState(false);
  const [excelUploadError, setExcelUploadError] = useState("");

  const handleFileUpload = (e: React.ChangeEvent<HTMLInputElement>) => {
    if (e.target.files) {
      const files = Array.from(e.target.files);
      setUploadedFiles(files);
      setShowUploadSuccess(true);
      setTimeout(() => setShowUploadSuccess(false), 5000);
    }
  };

  const handleExcelUpload = (e: React.ChangeEvent<HTMLInputElement>) => {
    setExcelUploadError("");
    if (e.target.files) {
      const files = Array.from(e.target.files);
      const invalidFiles: string[] = [];
      const validFiles: File[] = [];

      files.forEach((file) => {
        // Check if file is Excel (.xlsx or .xls)
        const isExcel = file.name.endsWith('.xlsx') || 
                       file.name.endsWith('.xls') || 
                       file.type === 'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet' ||
                       file.type === 'application/vnd.ms-excel';
        
        if (isExcel) {
          validFiles.push(file);
        } else {
          invalidFiles.push(file.name);
        }
      });

      if (invalidFiles.length > 0) {
        setExcelUploadError(`Invalid file type(s): ${invalidFiles.join(', ')}. Only Microsoft Excel files (.xlsx, .xls) are accepted.`);
        // Clear the input
        e.target.value = '';
      }

      if (validFiles.length > 0) {
        setExcelFiles(prevFiles => [...prevFiles, ...validFiles]);
        setShowExcelSuccess(true);
        setTimeout(() => setShowExcelSuccess(false), 5000);
      }
    }
  };

  const removeExcelFile = (index: number) => {
    setExcelFiles(prevFiles => prevFiles.filter((_, i) => i !== index));
  };

  return (
    <div className="space-y-12">
      {/* Hero Section */}
      <section className="text-center py-12 bg-gradient-to-r from-green-600 to-emerald-600 rounded-2xl text-white shadow-xl">
        <div className="max-w-3xl mx-auto px-4">
          <h1 className="text-4xl md:text-5xl font-bold mb-4">
            Welcome to ShambaPulse
          </h1>
          <p className="text-xl mb-2 text-green-50">
            Reducing food decay through AI-powered demand estimation, smart pricing, and optimized transport logistics
          </p>
          <p className="text-lg font-semibold text-green-100 mt-4">
            Quality Assurance as a Service • Transport as a Service • Investment as a Service
          </p>
        </div>
      </section>

      {/* Quality Assurance Platform */}
      <section className="max-w-5xl mx-auto">
        <div className="text-center mb-8">
          <div className="inline-flex items-center justify-center w-16 h-16 bg-gradient-to-br from-green-500 to-emerald-600 rounded-full mb-4 shadow-lg">
            <Shield className="w-8 h-8 text-white" />
          </div>
          <h2 className="text-3xl font-bold text-gray-800 mb-2">Quality Assurance Platform</h2>
          <p className="text-lg text-gray-600">
            Upload food test strips or quality reports for instant AI-powered analysis
          </p>
        </div>

        <Card className="border-2 border-green-200 shadow-xl bg-gradient-to-br from-green-50 via-white to-emerald-50">
          <CardHeader className="text-center pb-4">
            <CardTitle className="text-2xl text-green-800">Verify Your Produce Quality</CardTitle>
            <CardDescription className="text-base">
              Get instant quality certification and recommendations based on your test results
            </CardDescription>
          </CardHeader>
          <CardContent className="space-y-6">
            {/* Upload Area */}
            <div className="border-2 border-dashed border-green-300 rounded-lg p-8 bg-white hover:border-green-500 transition-all">
              <div className="text-center space-y-4">
                <div className="flex justify-center">
                  <div className="w-20 h-20 bg-green-100 rounded-full flex items-center justify-center">
                    <Upload className="w-10 h-10 text-green-600" />
                  </div>
                </div>
                <div>
                  <Label htmlFor="file-upload" className="text-lg font-semibold text-gray-800 cursor-pointer hover:text-green-600">
                    Click to upload or drag and drop
                  </Label>
                  <p className="text-sm text-gray-600 mt-2">
                    Supported: Images of food test strips, quality reports (JPG, PNG, PDF - Max 10MB)
                  </p>
                </div>
                <Input
                  id="file-upload"
                  type="file"
                  multiple
                  accept="image/*,.pdf"
                  onChange={handleFileUpload}
                  className="hidden"
                />
                <Button 
                  onClick={() => document.getElementById('file-upload')?.click()}
                  size="lg"
                  className="bg-green-600 hover:bg-green-700"
                >
                  <Upload className="w-5 h-5 mr-2" />
                  Select Files
                </Button>
              </div>
            </div>

            {/* Success Message */}
            {showUploadSuccess && uploadedFiles.length > 0 && (
              <Alert className="bg-green-50 border-green-300">
                <CheckCircle2 className="w-5 h-5 text-green-600" />
                <AlertDescription className="text-green-800">
                  <strong>Successfully uploaded {uploadedFiles.length} file(s)!</strong> Our AI is analyzing your quality reports...
                </AlertDescription>
              </Alert>
            )}

            {/* Uploaded Files Display */}
            {uploadedFiles.length > 0 && (
              <div className="space-y-2">
                <h4 className="font-semibold text-gray-800">Uploaded Files:</h4>
                <div className="space-y-2">
                  {uploadedFiles.map((file, index) => (
                    <div key={index} className="flex items-center gap-3 p-3 bg-gray-50 rounded-lg border border-gray-200">
                      <FileCheck className="w-5 h-5 text-green-600" />
                      <span className="flex-1 text-sm text-gray-700">{file.name}</span>
                      <Badge className="bg-green-100 text-green-700">
                        {(file.size / 1024).toFixed(1)} KB
                      </Badge>
                    </div>
                  ))}
                </div>
              </div>
            )}

            {/* What We Analyze */}
            <div className="grid md:grid-cols-3 gap-4 pt-4">
              <div className="text-center p-4 bg-gradient-to-br from-blue-50 to-blue-100 rounded-lg border border-blue-200">
                <div className="w-12 h-12 bg-blue-600 rounded-full flex items-center justify-center mx-auto mb-2">
                  <CheckCircle2 className="w-6 h-6 text-white" />
                </div>
                <h4 className="font-semibold text-blue-900 mb-1">pH Levels</h4>
                <p className="text-xs text-blue-700">Optimal acidity for freshness</p>
              </div>
              <div className="text-center p-4 bg-gradient-to-br from-purple-50 to-purple-100 rounded-lg border border-purple-200">
                <div className="w-12 h-12 bg-purple-600 rounded-full flex items-center justify-center mx-auto mb-2">
                  <CheckCircle2 className="w-6 h-6 text-white" />
                </div>
                <h4 className="font-semibold text-purple-900 mb-1">Contamination</h4>
                <p className="text-xs text-purple-700">Bacterial & chemical safety</p>
              </div>
              <div className="text-center p-4 bg-gradient-to-br from-green-50 to-green-100 rounded-lg border border-green-200">
                <div className="w-12 h-12 bg-green-600 rounded-full flex items-center justify-center mx-auto mb-2">
                  <CheckCircle2 className="w-6 h-6 text-white" />
                </div>
                <h4 className="font-semibold text-green-900 mb-1">Nutrient Content</h4>
                <p className="text-xs text-green-700">Vitamin & mineral analysis</p>
              </div>
            </div>

            {/* Benefits */}
            <div className="bg-gradient-to-r from-green-100 to-emerald-100 p-6 rounded-lg border border-green-300">
              <h4 className="font-semibold text-green-900 mb-3 flex items-center gap-2">
                <Shield className="w-5 h-5" />
                Why Use Quality Assurance?
              </h4>
              <div className="grid md:grid-cols-2 gap-3 text-sm text-green-800">
                <div className="flex items-start gap-2">
                  <CheckCircle2 className="w-4 h-4 mt-0.5 flex-shrink-0" />
                  <span>Get certified quality reports for better pricing</span>
                </div>
                <div className="flex items-start gap-2">
                  <CheckCircle2 className="w-4 h-4 mt-0.5 flex-shrink-0" />
                  <span>Build trust with buyers through verified quality</span>
                </div>
                <div className="flex items-start gap-2">
                  <CheckCircle2 className="w-4 h-4 mt-0.5 flex-shrink-0" />
                  <span>Access premium markets with quality certification</span>
                </div>
                <div className="flex items-start gap-2">
                  <CheckCircle2 className="w-4 h-4 mt-0.5 flex-shrink-0" />
                  <span>AI-powered recommendations to improve quality</span>
                </div>
              </div>
            </div>

            <div className="text-center">
              <Button size="lg" className="bg-gradient-to-r from-green-600 to-emerald-600 hover:from-green-700 hover:to-emerald-700">
                <FileCheck className="w-5 h-5 mr-2" />
                Get Quality Report
              </Button>
            </div>
          </CardContent>
        </Card>
      </section>

      {/* Main User Sections - Enhanced */}
      <section>
        <h2 className="text-3xl font-bold text-center mb-8 text-gray-800">Choose Your Role</h2>
        <div className="grid md:grid-cols-3 gap-6">
          {/* For Farmers */}
          <Link to="/farmers" className="group">
            <Card className="h-full hover:shadow-2xl transition-all duration-300 border-2 border-green-200 hover:border-green-400 bg-gradient-to-br from-green-50 to-emerald-50 cursor-pointer">
              <CardHeader className="text-center pb-4">
                <div className="w-24 h-24 mx-auto mb-4 bg-green-600 rounded-full flex items-center justify-center group-hover:scale-110 transition-transform shadow-lg">
                  <Sprout className="w-14 h-14 text-white" />
                </div>
                <CardTitle className="text-3xl font-bold text-green-800 mb-2">For Farmers</CardTitle>
                <CardDescription className="text-base text-gray-700">
                  Submit your produce and get AI-powered recommendations
                </CardDescription>
              </CardHeader>
              <CardContent className="text-center space-y-3">
                <div className="space-y-2 text-left">
                  <div className="flex items-center gap-2 text-sm text-gray-700">
                    <Smartphone className="w-4 h-4 text-green-600" />
                    <span>Smartphone & feature phone support</span>
                  </div>
                  <div className="flex items-center gap-2 text-sm text-gray-700">
                    <MessageSquare className="w-4 h-4 text-green-600" />
                    <span>AI chatbot assistance</span>
                  </div>
                  <div className="flex items-center gap-2 text-sm text-gray-700">
                    <TrendingUp className="w-4 h-4 text-green-600" />
                    <span>Best market prices</span>
                  </div>
                </div>
                <Button className="w-full mt-4 bg-green-600 hover:bg-green-700 text-lg py-6 group-hover:shadow-lg">
                  Get Started
                </Button>
              </CardContent>
            </Card>
          </Link>

          {/* For Transporters */}
          <Link to="/transporters" className="group">
            <Card className="h-full hover:shadow-2xl transition-all duration-300 border-2 border-blue-200 hover:border-blue-400 bg-gradient-to-br from-blue-50 to-cyan-50 cursor-pointer">
              <CardHeader className="text-center pb-4">
                <div className="w-24 h-24 mx-auto mb-4 bg-blue-600 rounded-full flex items-center justify-center group-hover:scale-110 transition-transform shadow-lg">
                  <Truck className="w-14 h-14 text-white" />
                </div>
                <CardTitle className="text-3xl font-bold text-blue-800 mb-2">For Transporters</CardTitle>
                <CardDescription className="text-base text-gray-700">
                  Register your vehicle and earn from transport jobs
                </CardDescription>
              </CardHeader>
              <CardContent className="text-center space-y-3">
                <div className="space-y-2 text-left">
                  <div className="flex items-center gap-2 text-sm text-gray-700">
                    <Package className="w-4 h-4 text-blue-600" />
                    <span>4 vehicle types supported</span>
                  </div>
                  <div className="flex items-center gap-2 text-sm text-gray-700">
                    <TrendingUp className="w-4 h-4 text-blue-600" />
                    <span>AI-optimized routes</span>
                  </div>
                  <div className="flex items-center gap-2 text-sm text-gray-700">
                    <Users className="w-4 h-4 text-blue-600" />
                    <span>Connect with farmers</span>
                  </div>
                </div>
                <Button className="w-full mt-4 bg-blue-600 hover:bg-blue-700 text-lg py-6 group-hover:shadow-lg">
                  Register Vehicle
                </Button>
              </CardContent>
            </Card>
          </Link>

          {/* For Buyers */}
          <Link to="/buyers" className="group">
            <Card className="h-full hover:shadow-2xl transition-all duration-300 border-2 border-purple-200 hover:border-purple-400 bg-gradient-to-br from-purple-50 to-pink-50 cursor-pointer">
              <CardHeader className="text-center pb-4">
                <div className="w-24 h-24 mx-auto mb-4 bg-purple-600 rounded-full flex items-center justify-center group-hover:scale-110 transition-transform shadow-lg">
                  <ShoppingCart className="w-14 h-14 text-white" />
                </div>
                <CardTitle className="text-3xl font-bold text-purple-800 mb-2">For Buyers</CardTitle>
                <CardDescription className="text-base text-gray-700">
                  Access fresh produce with quality assurance
                </CardDescription>
              </CardHeader>
              <CardContent className="text-center space-y-3">
                <div className="space-y-2 text-left">
                  <div className="flex items-center gap-2 text-sm text-gray-700">
                    <Sprout className="w-4 h-4 text-purple-600" />
                    <span>Fresh from verified farmers</span>
                  </div>
                  <div className="flex items-center gap-2 text-sm text-gray-700">
                    <TrendingDown className="w-4 h-4 text-purple-600" />
                    <span>Competitive pricing</span>
                  </div>
                  <div className="flex items-center gap-2 text-sm text-gray-700">
                    <Package className="w-4 h-4 text-purple-600" />
                    <span>Bulk & individual orders</span>
                  </div>
                </div>
                <Button className="w-full mt-4 bg-purple-600 hover:bg-purple-700 text-lg py-6 group-hover:shadow-lg">
                  Browse Produce
                </Button>
              </CardContent>
            </Card>
          </Link>
        </div>
      </section>

      {/* Problem Statement */}
      <section className="max-w-4xl mx-auto">
        <Card className="border-2 border-orange-200 bg-orange-50/50">
          <CardHeader>
            <CardTitle className="text-2xl text-orange-800">The Challenge</CardTitle>
          </CardHeader>
          <CardContent>
            <p className="text-lg text-gray-700">
              Farmers lose significant revenue due to crop decay from delayed sales. 
              ShambaPulse uses AI to analyze demand patterns, suggest optimal pricing, 
              and connect farmers with the right transporters and buyers - ensuring fresh 
              produce reaches the market quickly.
            </p>
          </CardContent>
        </Card>
      </section>

      {/* How It Works */}
      <section>
        <h2 className="text-3xl font-bold text-center mb-8 text-gray-800">How ShambaPulse Works</h2>
        <div className="grid md:grid-cols-3 gap-6">
          <Card className="hover:shadow-lg transition-shadow">
            <CardHeader>
              <Sprout className="w-12 h-12 text-green-600 mb-2" />
              <CardTitle>Farmers Submit Produce</CardTitle>
              <CardDescription>Via smartphone or feature phone (SMS)</CardDescription>
            </CardHeader>
            <CardContent>
              <p className="text-sm text-gray-600">
                Farmers can upload produce information using images, voice recordings, 
                or simple text messages. Our AI chatbot helps gather all necessary details.
              </p>
            </CardContent>
          </Card>

          <Card className="hover:shadow-lg transition-shadow">
            <CardHeader>
              <TrendingUp className="w-12 h-12 text-blue-600 mb-2" />
              <CardTitle>AI Analyzes Market</CardTitle>
              <CardDescription>Real-time demand and pricing insights</CardDescription>
            </CardHeader>
            <CardContent>
              <p className="text-sm text-gray-600">
                Our AI engine processes market demand, supply patterns, transport availability, 
                and traffic data to generate optimal recommendations.
              </p>
            </CardContent>
          </Card>

          <Card className="hover:shadow-lg transition-shadow">
            <CardHeader>
              <Truck className="w-12 h-12 text-purple-600 mb-2" />
              <CardTitle>Smart Matching</CardTitle>
              <CardDescription>Connect with buyers & transporters</CardDescription>
            </CardHeader>
            <CardContent>
              <p className="text-sm text-gray-600">
                Farmers are matched with buyers and transporters based on cost, 
                convenience, and freshness requirements.
              </p>
            </CardContent>
          </Card>
        </div>
      </section>

      {/* Value Proposition */}
      <section>
        <h2 className="text-3xl font-bold text-center mb-8 text-gray-800">Unique Value Proposition</h2>
        <div className="grid md:grid-cols-2 gap-6 max-w-4xl mx-auto">
          <Card className="bg-gradient-to-br from-blue-50 to-blue-100 border-blue-200">
            <CardHeader>
              <MessageSquare className="w-10 h-10 text-blue-600 mb-2" />
              <CardTitle>Inclusive Technology</CardTitle>
            </CardHeader>
            <CardContent>
              <p className="text-gray-700">
                Works with both smartphones and feature phones through bulk SMS, 
                ensuring even the informal sector has access to market data and demand patterns.
              </p>
            </CardContent>
          </Card>

          <Card className="bg-gradient-to-br from-green-50 to-green-100 border-green-200">
            <CardHeader>
              <Smartphone className="w-10 h-10 text-green-600 mb-2" />
              <CardTitle>AI-Powered Insights</CardTitle>
            </CardHeader>
            <CardContent>
              <p className="text-gray-700">
                Advanced AI determines the best price based on supply/demand, 
                optimal transport based on cost and traffic, and assesses freshness risk.
              </p>
            </CardContent>
          </Card>
        </div>
      </section>

      {/* CTA Section */}
      <section className="text-center py-12 bg-white rounded-2xl shadow-lg">
        <h2 className="text-3xl font-bold mb-4 text-gray-800">Ready to Get Started?</h2>
        <p className="text-lg text-gray-600 mb-6 max-w-2xl mx-auto">
          Join thousands of farmers, transporters, and buyers using ShambaPulse to reduce waste and increase profits.
        </p>
        <div className="flex flex-wrap gap-4 justify-center">
          <Button asChild size="lg" className="bg-green-600 hover:bg-green-700">
            <Link to="/farmers">Submit Your Produce</Link>
          </Button>
          <Button asChild size="lg" variant="outline">
            <Link to="/recommendations">View AI Insights</Link>
          </Button>
        </div>
      </section>

      {/* Investment as a Service Platform */}
      <section className="max-w-5xl mx-auto">
        <div className="text-center mb-8">
          <div className="inline-flex items-center justify-center w-16 h-16 bg-gradient-to-br from-blue-500 to-indigo-600 rounded-full mb-4 shadow-lg">
            <DollarSign className="w-8 h-8 text-white" />
          </div>
          <h2 className="text-3xl font-bold text-gray-800 mb-2">Investment as a Service</h2>
          <p className="text-lg text-gray-600">
            Secure funding for your farm by uploading your financial records
          </p>
        </div>

        <Card className="border-2 border-blue-200 shadow-xl bg-gradient-to-br from-blue-50 via-white to-indigo-50">
          <CardHeader className="text-center pb-4">
            <CardTitle className="text-2xl text-blue-800">Access Farm Investment Opportunities</CardTitle>
            <CardDescription className="text-base">
              Upload your financial records for AI-powered creditworthiness assessment and investor matching
            </CardDescription>
          </CardHeader>
          <CardContent className="space-y-6">
            {/* Important Notice */}
            <Alert className="bg-blue-50 border-blue-300">
              <FileSpreadsheet className="w-5 h-5 text-blue-600" />
              <AlertDescription className="text-blue-800">
                <strong>Excel Documents Only:</strong> This platform only accepts Microsoft Excel files (.xlsx, .xls) for financial record uploads. Other file formats will be rejected.
              </AlertDescription>
            </Alert>

            {/* Upload Area */}
            <div className="border-2 border-dashed border-blue-300 rounded-lg p-8 bg-white hover:border-blue-500 transition-all">
              <div className="text-center space-y-4">
                <div className="flex justify-center">
                  <div className="w-20 h-20 bg-blue-100 rounded-full flex items-center justify-center">
                    <FileSpreadsheet className="w-10 h-10 text-blue-600" />
                  </div>
                </div>
                <div>
                  <Label htmlFor="excel-upload" className="text-lg font-semibold text-gray-800 cursor-pointer hover:text-blue-600">
                    Upload Financial Records
                  </Label>
                  <p className="text-sm text-gray-600 mt-2">
                    <strong>Accepted formats:</strong> Microsoft Excel (.xlsx, .xls) only
                  </p>
                  <p className="text-xs text-gray-500 mt-1">
                    Include: Income statements, balance sheets, cash flow reports, expense records
                  </p>
                </div>
                <Input
                  id="excel-upload"
                  type="file"
                  multiple
                  accept=".xlsx,.xls,application/vnd.openxmlformats-officedocument.spreadsheetml.sheet,application/vnd.ms-excel"
                  onChange={handleExcelUpload}
                  className="hidden"
                />
                <Button 
                  onClick={() => document.getElementById('excel-upload')?.click()}
                  size="lg"
                  className="bg-blue-600 hover:bg-blue-700"
                >
                  <FileSpreadsheet className="w-5 h-5 mr-2" />
                  Select Excel Files
                </Button>
              </div>
            </div>

            {/* Error Message */}
            {excelUploadError && (
              <Alert className="bg-red-50 border-red-300">
                <AlertTriangle className="w-5 h-5 text-red-600" />
                <AlertDescription className="text-red-800">
                  <strong>Upload Failed:</strong> {excelUploadError}
                </AlertDescription>
              </Alert>
            )}

            {/* Success Message */}
            {showExcelSuccess && excelFiles.length > 0 && (
              <Alert className="bg-green-50 border-green-300">
                <CheckCircle2 className="w-5 h-5 text-green-600" />
                <AlertDescription className="text-green-800">
                  <strong>Successfully uploaded Excel file(s)!</strong> Our AI is analyzing your financial records for investment opportunities...
                </AlertDescription>
              </Alert>
            )}

            {/* Uploaded Excel Files Display */}
            {excelFiles.length > 0 && (
              <div className="space-y-2">
                <h4 className="font-semibold text-gray-800">Uploaded Financial Records:</h4>
                <div className="space-y-2">
                  {excelFiles.map((file, index) => (
                    <div key={index} className="flex items-center gap-3 p-3 bg-gray-50 rounded-lg border border-gray-200">
                      <FileSpreadsheet className="w-5 h-5 text-blue-600" />
                      <span className="flex-1 text-sm text-gray-700">{file.name}</span>
                      <Badge className="bg-blue-100 text-blue-700">
                        {(file.size / 1024).toFixed(1)} KB
                      </Badge>
                      <Button
                        variant="ghost"
                        size="sm"
                        onClick={() => removeExcelFile(index)}
                        className="text-red-600 hover:text-red-700 hover:bg-red-50"
                      >
                        Remove
                      </Button>
                    </div>
                  ))}
                </div>
              </div>
            )}

            {/* What We Analyze */}
            <div className="grid md:grid-cols-3 gap-4 pt-4">
              <div className="text-center p-4 bg-gradient-to-br from-green-50 to-green-100 rounded-lg border border-green-200">
                <div className="w-12 h-12 bg-green-600 rounded-full flex items-center justify-center mx-auto mb-2">
                  <CheckCircle2 className="w-6 h-6 text-white" />
                </div>
                <h4 className="font-semibold text-green-900 mb-1">Revenue Analysis</h4>
                <p className="text-xs text-green-700">Income trends & growth potential</p>
              </div>
              <div className="text-center p-4 bg-gradient-to-br from-blue-50 to-blue-100 rounded-lg border border-blue-200">
                <div className="w-12 h-12 bg-blue-600 rounded-full flex items-center justify-center mx-auto mb-2">
                  <CheckCircle2 className="w-6 h-6 text-white" />
                </div>
                <h4 className="font-semibold text-blue-900 mb-1">Cash Flow</h4>
                <p className="text-xs text-blue-700">Liquidity & payment capacity</p>
              </div>
              <div className="text-center p-4 bg-gradient-to-br from-purple-50 to-purple-100 rounded-lg border border-purple-200">
                <div className="w-12 h-12 bg-purple-600 rounded-full flex items-center justify-center mx-auto mb-2">
                  <CheckCircle2 className="w-6 h-6 text-white" />
                </div>
                <h4 className="font-semibold text-purple-900 mb-1">Credit Score</h4>
                <p className="text-xs text-purple-700">Creditworthiness rating</p>
              </div>
            </div>

            {/* Investment Benefits */}
            <div className="bg-gradient-to-r from-blue-100 to-indigo-100 p-6 rounded-lg border border-blue-300">
              <h4 className="font-semibold text-blue-900 mb-3 flex items-center gap-2">
                <DollarSign className="w-5 h-5" />
                Why Seek Investment Through ShambaPulse?
              </h4>
              <div className="grid md:grid-cols-2 gap-3 text-sm text-blue-800">
                <div className="flex items-start gap-2">
                  <CheckCircle2 className="w-4 h-4 mt-0.5 flex-shrink-0" />
                  <span>Access to verified investors interested in agriculture</span>
                </div>
                <div className="flex items-start gap-2">
                  <CheckCircle2 className="w-4 h-4 mt-0.5 flex-shrink-0" />
                  <span>AI-powered credit assessment for better rates</span>
                </div>
                <div className="flex items-start gap-2">
                  <CheckCircle2 className="w-4 h-4 mt-0.5 flex-shrink-0" />
                  <span>Transparent financial evaluation process</span>
                </div>
                <div className="flex items-start gap-2">
                  <CheckCircle2 className="w-4 h-4 mt-0.5 flex-shrink-0" />
                  <span>Flexible funding options tailored to farming cycles</span>
                </div>
              </div>
            </div>

            {/* Investment Tiers */}
            <div>
              <h4 className="font-semibold text-gray-800 mb-4">Available Investment Options:</h4>
              <div className="grid md:grid-cols-3 gap-4">
                <div className="p-4 border-2 border-green-200 rounded-lg bg-green-50 hover:shadow-md transition-shadow">
                  <h5 className="font-bold text-green-900 mb-2">Risk-Sharing Facilities</h5>
                  <p className="text-sm text-green-700 mb-2">Mitigate investment risks through shared responsibility models</p>
                  <p className="text-xs text-green-600">Protect your investment with co-guarantee mechanisms</p>
                </div>
                <div className="p-4 border-2 border-blue-200 rounded-lg bg-blue-50 hover:shadow-md transition-shadow">
                  <h5 className="font-bold text-blue-900 mb-2">Growth Capital</h5>
                  <p className="text-2xl font-bold text-blue-700 mb-2">KES 100K - 1M</p>
                  <p className="text-xs text-blue-600">Medium-term funding for expansion and infrastructure</p>
                </div>
                <div className="p-4 border-2 border-purple-200 rounded-lg bg-purple-50 hover:shadow-md transition-shadow">
                  <h5 className="font-bold text-purple-900 mb-2">Scale Investment</h5>
                  <p className="text-2xl font-bold text-purple-700 mb-2">KES 1M+</p>
                  <p className="text-xs text-purple-600">Long-term funding for large-scale operations</p>
                </div>
                <div className="p-4 border-2 border-indigo-200 rounded-lg bg-indigo-50 hover:shadow-md transition-shadow">
                  <h5 className="font-bold text-indigo-900 mb-2">SME Ventures Program</h5>
                  <p className="text-sm text-indigo-700 mb-2">Specialized support for small & medium agricultural enterprises</p>
                  <p className="text-xs text-indigo-600">Business development and market access</p>
                </div>
                <div className="p-4 border-2 border-teal-200 rounded-lg bg-teal-50 hover:shadow-md transition-shadow">
                  <h5 className="font-bold text-teal-900 mb-2">Technical Assistance & Advisory</h5>
                  <p className="text-sm text-teal-700 mb-2">Expert guidance on farming practices and business strategy</p>
                  <p className="text-xs text-teal-600">Access to agricultural specialists and consultants</p>
                </div>
                <div className="p-4 border-2 border-cyan-200 rounded-lg bg-cyan-50 hover:shadow-md transition-shadow">
                  <h5 className="font-bold text-cyan-900 mb-2">Regional Trade Support</h5>
                  <p className="text-sm text-cyan-700 mb-2">Expand your market reach across regional borders</p>
                  <p className="text-xs text-cyan-600">Export facilitation and cross-border trade assistance</p>
                </div>
                <div className="p-4 border-2 border-amber-200 rounded-lg bg-amber-50 hover:shadow-md transition-shadow">
                  <h5 className="font-bold text-amber-900 mb-2">Capacity Building</h5>
                  <p className="text-sm text-amber-700 mb-2">Training programs to enhance farming skills and productivity</p>
                  <p className="text-xs text-amber-600">Workshops, certifications, and knowledge transfer</p>
                </div>
              </div>
            </div>

            <div className="text-center">
              <Button 
                size="lg" 
                className="bg-gradient-to-r from-blue-600 to-indigo-600 hover:from-blue-700 hover:to-indigo-700"
                disabled={excelFiles.length === 0}
              >
                <Investment className="w-5 h-5 mr-2" />
                Submit for Investment Review
              </Button>
              {excelFiles.length === 0 && (
                <p className="text-xs text-gray-500 mt-2">Upload at least one Excel file to proceed</p>
              )}
            </div>
          </CardContent>
        </Card>
      </section>
    </div>
  );
}

## Contents of Github








### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

### Authors

<a 
</a>

- **John Maina**
- **Dominic**
- **Lawrence**

   ### Demo videos

  
  ### Demo links
  https://medium-tech-20229072.figma.site/

  https://apps.powerapps.com/play/e/a05e186e-bb6d-eae3-8be7-b1a6c8ad114e/a/418fd900-c68c-428c-b39e-a53b7f9e9f9b?tenantId=6e2cc058-79af-4df8-92e6-ee6e0d1dea3e&hint=e5063b3c-9f5a-47d3-b602-946d27b1d865&source=sharebutton&sourcetime=1771223055624

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.


