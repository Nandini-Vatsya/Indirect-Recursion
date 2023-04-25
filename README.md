# Indirect-Recursion
<br>
<br>
<br>
<b><ins>What is Recursion? </b></ins><br>
The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called a recursive function. Using recursive algorithm, certain problems can be solved quite easily. Examples of such problems are Towers of Hanoi (TOH), Inorder/Preorder/Postorder Tree Traversals, DFS of Graph, etc.<br>
<br>
<b><ins>Types of Recursions: </b></ins><br>
Recursion are mainly of two types depending on whether a function calls itself from within itself or more than one function call one another mutually. The first one is called direct recursion and another one is called indirect recursion.<br>
<br>
<br>
<b><ins>Indirect Recursion: </b></ins>In this recursion, there may be more than one functions and they are calling one another in a circular manner.<br>
<br>
![Capture34](https://user-images.githubusercontent.com/125802204/234304075-f9010b65-8ea7-49dd-b944-36fe8b5fd5c8.jpg)


<br>
From the above diagram fun(A) is calling for fun(B), fun(B) is calling for fun(C) and fun(C) is calling for fun(A) and thus it makes a cycle.<br>
<br>
<br>
<b><ins>Output</b></ins><br>
<br>
<img width="910" alt="Indirect Recursion" src="https://user-images.githubusercontent.com/125802204/234302783-946050ef-70a9-4268-8797-da1657081b6a.png">

