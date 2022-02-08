---
layout: default
title: "Project Definition"
nav_order: 1
has_children: false
---

# **Project Definition**

## **Objectives:**

1. Be able to conduct the software change process;

2. Be able to write software documents (requirement specification, design document, test cases);

3. Work in the team environment;

4. Practice presentation and communication skills requested by software engineering.

## **Team Setup:**

This course project is team based. Students attending this course will be grouped into 4 teams (5 students per team) and focus on software maintenance of an open-source software Mango. Teams will work on 5 new features of Mango, which are provided through feature description documents.  These 5 features are supposed to include 2 easy ones, 2 medium difficult ones and 1 hard one.

Each team needs to choose a member as the project leader (with 5% bonus of the final project points). The project leader has the responsibility of managing the project and coordinating tasks. Each feature will have a feature champion, who will lead this feature development. Among the 5 team members, one member will be the feature champion for the two easy features. Each medium difficult feature will have a single feature champion. The hard feature will have two feature campions including the project leader and one more team member.

All documents, presentation slides, source codes and other deliverables must be uploaded to the moodleMoodle before the due date. At the end of the semester, the team members will do a cross evaluation of contribution among each other.

Grading rules for each deliverable will be posted on moodleMoodle assignments. Late submission will not be accepted due to the presentation schedule.

## **Feature Change Requests:**

This course project is team based. Students attending this course will be grouped into 4 teams (5 students per team) and focus on software maintenance of a well-known open source software xfig. Teams will work on 4 new features of xfig, which are listed below.


<table>
    <tbody>
        <tr>
            <td>
                <p>
                    <strong>Feature</strong>
                </p>
            </td>
            <td>
                <p>
                    <strong>Current Behaviors</strong>
                </p>
            </td>
            <td>
                <p>
                    <strong>Expected Behaviors</strong>
                </p>
            </td>
            <td>
                <p>
                    <strong>Difficulty</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>
                    <a href="https://github.com/Da-vid21/xfig-3.2.8a/issues/2">Enhanced Rotation #1</a>
                </p>
            </td>
            <td>
                <p>
                    Currently all Xfig objects can only be rotated along a user-selected point by a preset degree either clockwise or counterclockwise (0, 90, 180, and 270). Figure 1 illustrates rotation of a rectangle by 90 degrees. However, angles other than the preset four values are not supported. In fact, when a user attempts to enter any unsupported angle through the angle setting window shown in Figure 2, Xfig will disable this feature by ignoring it
                </p>
            </td>
            <td>
                <p>
                    Enhance the current rotation feature by adding support for any angles in either clockwise or counterclockwise direction, e.g., 30 or 45 degrees. Once the user enters the angle in the angle setting window shown in Figure 2, the object should rotate by the specified degree and direction, rather than having this feature disabled. 
                </p>
            </td>
            <td>
                <p>
                    <strong class="label label-green">Easy</strong> (Est. 2 files; 18 LOC)
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>
                    <a href="https://github.com/Da-vid21/xfig-3.2.8a/issues/1">Auto Increment Default Depth Value #2</a>
                </p>
            </td>
            <td>
                <p>
                    Currently, each Xfig object (e.g., arc, line, rectangle) has a property called depth, which is used to identify and group the objects on the same layer. In Xfig, the valid range of depth is 0 to 999, and the default value is 50 for any newly created object. Also, it means that all objects created are on the same layer by default. Figure 1 shows the default depth value is 50 for the three objects on canvas. 
                </p>
            </td>
            <td>
                <p>
                    This task requests to change the way of assigning the default depth value to newly created. The default depth will be increased with a certain interval (e.g., 1) for new created objects accordingly. For example, the default depth for the 1st object created on the canvas is 50, and then the 2nd one will be 51, and so on. Also, it means that all objects created are on different layers by default.
                </p>
            </td>
            <td>
                <p>
                    <strong class="label label-green">Easy</strong> (Est. 9 files; 33 LOC)
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>
                    <a href="https://github.com/Da-vid21/xfig-3.2.8a/issues/3">Shortcut Button for Toggling Unit of Length #3</a>
                </p>
            </td>
            <td>
                <p>
                    Currently the default unit of length is Metric (centimeter, or cm), which can be changed to Imperial through the menu (Menu -> Edit -> Set Units), which is shown in Figure 1. However, Xfig users always prefer doing actions through shortcut buttons on the Editing Mode Panel on the left hand side of Xfig.
                </p>
            </td>
            <td>
                <p>
                    Create a unit toggling button on the Editing Mode Panel on the left hand side of Xfig. This toggling button should deliver the same behavior as the menu version: First click will change the unit to Imperial, and one more clicking will change it back to Metric.
                </p>
            </td>
            <td>
                <p>
                    <strong class="label label-green">Easy</strong> (Est. 5 files; 30 LOC)
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>
                    <a href="https://github.com/Da-vid21/xfig-3.2.8a/issues/4">Shortcut Button for Undo #4</a>
                </p>
            </td>
            <td>
                <p>
                    Currently the Undo edit tool allows a user to undo the last operation such as object creation, deletion, or modification. As shown in Figure 1, the Undo edit tool is accessed through the menu (Menu --> Edit --> Undo). However, Xfig users always prefer doing actions through the shortcut buttons on the Editing Mode Panel shown at the left hand side of Xfig, since it is directly visible and quick with one rather than two clicks.
                </p>
            </td>
            <td>
                <p>
                    Create a shortcut button for Undo on the Editing Mode Panel at the left hand side of Xfig. The behavior should be the same as the default Undo: First click will undo the last operation, and one more clicking will redo it. 
                </p>
            </td>
            <td>
                <p>
                    <strong class="label label-green">Easy</strong> (Est. 3 files; 15 LOC)
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>
                    <a href="https://github.com/Da-vid21/xfig-3.2.8a/issues/5">Free Selection #5</a>
                </p>
            </td>
            <td>
                <p>
                    Currently Xfig allows a user to select a single object and then move it. However, this is not the most efficient when the user has to move multiple objects while keeping their relative locations to each other
                </p>
            </td>
            <td>
                <p>
                    Allow a user to create a closed-loop shape that will select all objects within the shape. In the given solution, the chosen shape is a rectangle, but in practice this shape could be an ellipse, or a regular n-gon. Holding and dragging the left mouse button will move all selected objects simultaneously while keeping their relative positions unchanged. Releasing the left mouse button will determine the new location. Also add a new shortcut button in the Editing Mode Panel on the left hand side of Xfig. This procedure is demonstrated in Figure 1 below.
                </p>
            </td>
            <td>
                <p>
                    <strong class="label label-yellow">Medium</strong> (Est. 5 files; 640 LOC)
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>
                    <a href="https://github.com/Da-vid21/xfig-3.2.8a/issues/6">Quick Coloring #6</a>
                </p>
            </td>
            <td>
                <p>
                    Currently Xfig allows a user to specify both the fill color and the border color at the time of the object’s creation. If a user wishes to change the object’s fill and border color after creation, they first have to click the edit shortcut button and then on the object to pop up an edit menu. Figure 1 illustrates the current behavior through an example figure (a rectangle).
                </p>
            </td>
            <td>
                <p>
                    The current feature needs to be enhanced, since it is ineffective, especially when the user needs to specify the same fill and border colors for multiple objects. To improve this process, add a paint tool button in the Editing Mode Panel on the left hand side of Xfig. After selecting a fill color and a border color in the indicator panel for this feature, right-clicking an object will fill it with the selected fill color, and left-clicking will set it the selected border color.
                </p>
            </td>
            <td>
                <p>
                    <strong class="label label-yellow">Medium</strong> (Est. 7 files; 312 LOC)
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>
                    <a href="https://github.com/Da-vid21/xfig-3.2.8a/issues/7">Enhanced Undo/Redo #7</a>
                </p>
            </td>
            <td>
                <p>
                    Currently the Undo edit tool (Menu --> Edit --> Undo) allows a user to undo only the last operation such as object creation, deletion, or modification. This would deliver an unnatural behavior. For example, when Undo is clicked twice, the program will go back to the state before the first Undo rather than undoing the previous two actions. Multi-level undo is not supported. Figure 1 illustrates the current behavior through an example figure with three rectangles.
                </p>
            </td>
            <td>
                <p>
                    The current Undo feature needs to be enhanced to support multi-level undo. This new feature will allow a user to undo or redo an unlimited number of times. The maximum number of undo/redo operations is only limited by the amount of available memory determined by the computer system. Furthermore, the new feature must support the same set of drawing objects the current undo/redo operations support  without any change.
                </p>
            </td>
            <td>
                <p>
                    <strong class="label label-red">High</strong> (Est. 17 files; 850 LOC)
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>
                    <a href="https://github.com/Da-vid21/xfig-3.2.8a/issues/8">Exporting to VDX Format #8</a>
                </p>
            </td>
            <td>
                <p>
                    As shown in Figure 1, currently Xfig allows a user to export a figure into multiple figure formats, such as PNG, EPS, JPG, PDF, and SVG, but does not support VDX, a well-documented XML Schema-based format that is supported by Microsoft Visio, the successful drawing tool in the MS Office suite.
                </p>
            </td>
            <td>
                <p>
                    Add the VDX export format into Xfig. Once Xfig can export  figures into VDX format, a user can use the MS Visio tool to  edit figures generated by Xfig. Note that the new version of VDX has been renamed to VSDX (Visio XML file format [1]) since 2013.  Although we still call it VDX here, students need to follow the latest VDX specification, i.e., VSDX. Figure 2 shows the sample VDX export window.
                </p>
            </td>
            <td>
                <p>
                    <strong class="label label-red">High</strong> (Est. 10 files; 969 LOC)
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>
                    <a href="https://github.com/Da-vid21/xfig-3.2.8a/issues/9">Send to Back & Bring to Front #9</a>
                </p>
            </td>
            <td>
                <p>
                    Currently each Xfig object (e.g., arc, line, rectangle) has a property called depth, which is used to group objects that share the same depth into the same layer. This feature is used to organize objects in a hierarchical fashion. To change the layer that an Xfig object belongs to in the hierarchy, a user changes its depth through the Depth Panel shown in the right hand side of Xfig (Figure 1). However, it is not convenient, especially when users want to reorganize multiple objects that share the same depth and when objects overlap each other.
                </p>
            </td>
            <td>
                <p>
                    To provide users with a more flexible and efficient workflow, a better way is to add two new shortcut buttons called “send to back” and “bring to front” in the Editing Mode Panel on the left hand side of Xfig. These buttons will change the depth of the selected object and other relevant objects to put the selected one to the bottom/top layer on the canvas.
                </p>
            </td>
            <td>
                <p>
                    <strong class="label label-red">High</strong> (Est. 5 files; 272 LOC)
                </p>
            </td>
        </tr>
    </tbody>
</table>

## **Grading**

- 70 points (projects)

> – xfig Architecture Document & Presentation: 10 points
>
> – New Features Analysis (a.k.a., Requirements): 10 points
>
> – Design (Concept Location & Impact Analysis): 10 points
>
> – Test Cases & Results: 10 points
>
> – Code Inspection: 10 points
>
> – New Features: 20 points (10 points/feature, feature champion: your feature + sum of other features/3, team leader: sum of all features/2)

- 5 points – xfig Supporting Technique – X Window Document & Presentation
- 5 points - Cross Evaluation of Contribution of Team Members
- 5 points – Essay for Ethics and Social Issues in Software Engineering under the COVID-19 pandemic (minimal 2 pages excluding references)
- 15 points – Exam

### **Criteria**

- Grading rule for each assignment will be posted on moodle.

## **Deliverables & Schedule & Grading Rules:**

All documents, presentation slides, source codes and other deliverables must be uploaded to the moodle before the due date. Grading rules for each deliverable are shown below. Late submission will not be accepted unless the instructor has been notified with an acceptable reason (e.g., health issues, travel for academic conferences or interviews, …, on a case by case basis).

### **1 - _Xfig Architecture Diagrams (Due: February 8, 2021)_**

> (1). You can use any tool including Xfig itself to draw the UML diagrams extracted from Xfig source codes. The diagrams include one static diagram (similar to C++ class diagram, called pseudo class diagram) and one activity diagram (3 points for each of them: 3 - Good, 2 - Fair, 1 - Poor). Your diagrams need to have significant improvement compared to the sample ones. Otherwise, you cannot get the points.
>
> (2). One-page summary explaining these two diagrams and your improvements in details is requested. (2 point)
>
> (3). Presentation slides are not requested. You can present based on your diagrams and the summary. (2 points)
>
> Note that the rules for the absence of presentation are the same as before.

### **2 - _Requirement Book (Due: March 1, 2021)_**

> (1). Requirement Book for new features (6 points per feature, and the final grading is the average points of all features)
>
> (Very Poor: 1 point, Poor: 2 point, Fair: 3 points, Fair/Good: 4 points, Good: 5 points, Excellent: 6 points)
>
> Grading Criteria:
>
> Very Poor: No difference compared to the feature change requests.
>
> Poor: Difference can be observed, but requirements are not itemized.
>
> Fair: Difference can be observed, and requirements have been itemized.
>
> Fair/Good: All itemized requirements are feasible, testable, concise, and clear.
>
> Good: Sufficient interaction with other relevant features have been included.
>
> Excellent: Smart, effective and user friendly solutions have been proposed to address the feature interaction.
>
> (2). Presentation: 2 points (must attend the presentation to get this credit)
>
> (3). Feature Change Request Table: 2 points

### **3 - _Design (Concept Location & Impact Analysis) (Due: March 15, 2021)_**

> (1). Updating the requirement book based on the comments from the instructor (2 points): Note - you need to highlight the changes, and create the change history table to get this credit.
>
> (2). Updating the diagrams to support the design (1 point): Note - you cannot get this credit if your diagram updating has no connection with the needs of your concept location and impact analysis.
>
> (3). Presentation (2 points): You must attend the presentation to get this credit.
>
> (4). Feature (5 points): 5 points per feature (2 points for concept location, and 3 points for impact analysis), and "the grading = # points of total features / # of features"
>
> (i). Concept Location:
>
> Describing the progress of building and executing the query for your feature - 1 point
>
> Concept location result - 1 point
>
> (ii). Impact Analysis: Note - you must follow the methodology introduced in the lecture and take use of your static diagram, otherwise no credit will be obtained
>
> Grading Criteria:
>
> Poor - 1 point: only provide the impact analysis result and mark it on your static diagram.
>
> Fair - 2 points: provide the impact analysis result and mark it on your static diagram. Also, the progress and its explanation are given in detail.
>
> Good - 3 points: Two different coding solutions have been evaluated based on their impact analysis results, and the decision has been given based on the evaluation result. Note - if it is impossible to have 2 alternative solutions, please explain it in detail.
>
> Note that please submit your requirement book revision, static diagram revision and design document in one zip file.

### **4 - _Test Cases & Test Results (Due: April 28, 2021)_**

> Grading (10 points in total):
>
> Test case and requirement book traceability table: 1 point
>
> Presentation: 2 points (Note: you must attend the presentation to get this credit unless an acceptable reason has been sent to the instructor before the presentation)
>
> Test Cases: 4 points per feature and the final grading is the average points of all your features.
>
> Grading Criteria:
>
> Excellent - 4 points: Full coverage to all requirements has been reached, and all test cases can be considered full test cases. Note - a test case with all key elements (i.e., case ID, title, dependency, input specification, test steps, and output specification) can be considered a full test case.
>
> Good - 3 points: Full coverage to all requirements has been reached, and a few test cases have issues to be considered a full test case.
>
> Fair - 2 points: Full coverage to all requirements has been reached, and a significant number of test cases have issues in being considered full test cases.
>
> Poor - 1 point: Full coverage to all requirements has NOT been reached, and a significant number of test cases have issues in being considered full test cases.
>
> Test Results: 3 points (test results are due by Apr. 26, 2021 10:20am)

### **5 - _Code Inspection (Due: April 28, 2021)_**

> This assignment is due by the last class (April 28, 2021 10:20am). However, the moderator needs to submit the author's summary and reader's log before your code inspection meeting. The in-meeting log and final summary can be appended here by the due date.
>
> Please refer to our coding and code inspection preparing slides for details.

### **6 - _Features (Due: April 28, 2021)_**

> (1). Coding is due by Apr. 28, 2021 before the class, and all requirements need to be demonstrated in the class;
>
> (2). Commit all codes into the GitHub repository by Apr. 28, 2021 before the class, and a copy of source codes of xfig needs to be submitted here.
>
> (3). Pass all test cases (the test log needs to be submitted by Apr. 28, 2021 before the class) Note: the same moodle assignment as test cases
