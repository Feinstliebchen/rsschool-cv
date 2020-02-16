# Anastasia Kalinina

## Personal Information

Phone:	+7 952 788 6829

E-mail:	vergiesmichnicht@mail.ru

## Summary of Experience

* *Operating systems*: Windows, Android, Linux
* *Tools & Programs*: CRM systems (SAP), BI systems (Oracle BI, Microstrategy); MS Office Components; bug tracker systems (Redmine, Jira,  Argus-ktp, Lotus); personal management system (Teleopti);
* *Programming languages*: JavaScript, SQL, TypeScript;
* *Documentation management*: manipulation of data and documents (instructions, sales out), processing customers’ requests;
* *Language skills*: English – upper-intermediate, German – upper-intermediate (C1)

#### Code example:

`#include <iostream>

#include "FileParser.h"
#include "CircleCalculator.h"

int main(int argc, char** argv)
{
    if (argc < 2)
    {
        return 1;
    }

    std::string filename(argv[1]);

    FileParser parser(filename);

    std::list<Circle> inCircles;

    parser.parseCircles(inCircles);

    std::vector<Circle> outCircles;

    CircleCalculator calculator(inCircles);

    calculator.findBiggestWithNoIntersection(outCircles);

    if (outCircles.empty())
    {
        std::cout << "not found" << std::endl;
    }

    for (const auto & circle : outCircles )
    {
        std::cout << circle.getId() << std::endl;
    }

    return 0;
}
``

## Employment History

4.02.2014 – 28.05.2017  Kelly Services CIS (on behalf of Intel) –  Data Quality Analyst
-	Providing support by updating the total amount of the data, analyzing information needs, consulting database, integration and testing new services, solving problems regarding marketing program, analyzing of risks and reasons of errors, preparation of documents, professional interaction with the customers from Intel side.
Award: for support, commitment and effort of implementation of new system (by Intel’s Management).


9.05.2017 – 13.05.2018  AO Transset – Project Administrator
-	Collecting and processing statistical data, description of business processes, development of accompanying documentation

14.05.2018 – 14.10.2019 PAO Rostelekom – Analyst
-	Analyzing and providing statistic data regarding results of     technical support, Workload forecast, Analyzing and calculation of technical support's requirements, Maintaining of the projects (improving provided services' quality)

16.10.2019 - present OOO Gamma-Region – Software Validation Engineer
-	Test scheduling and describing, Software validation, Analyzing validation results, Creation of test-plans and test-cases, Bag classification, Documentation implementing (Queuing system testing: central system, local system, operator’s virtual desk, panel; Information panel testing)

## Education

2009 – 2014 	Linguistics University of Nizhny Novgorod
Faculty of Romance and Germanic languages – Specialist

2015 - 2017 Lobachevsky State University – National Research University
Institute of Economics and Entrepreneurship (Psychology of personality) – Master
Publication: Manipulation in pedagogics. Research: Leadership of students in computer science field.
