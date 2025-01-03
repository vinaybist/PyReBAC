# PyReBAC
A python implementation of ReBAC aka Relationship based access control

Key components:

Core: Stores entities, relationships (graph), and policies<br>
Management Layer: Handles CRUD operations<br>
Authorization Engine: Finds paths and checks access permissions<br>
public UI: Provides interface for external interactions<br>




    Test Case: Team Document Access Control
    <br>
    Scenario:<br>
    - Alice (user1) is a member of Engineering team (team1)
    - Engineering team owns a Project Specs document (doc1)
    - Policy allows team members to read team-owned documents
    <br></br>
    Expected Results:
    1. Alice should have read access to Project Specs (True)
    2. Bob (user2), not in team, should not have access (False)
    <br>
![image](https://github.com/user-attachments/assets/d8711ad0-4b43-432f-9a79-51ee469eff4b)

