<!-- Centered top image -->
<p align="center">
  <img src="https://github.com/SpawnCampGames/Documentation/blob/main/gfx/SPWN_DOC.png" width="307" height="91" alt="SPWN Logo">
</p>

## 📗SPWN DOCS
```csharp
using SPWN;
```

>[!IMPORTANT]
> Don't forget to include the **using** statement. ☝️

<details>
<summary>📗Dbug.cs</summary>

---
Custom `Debug.Log` Extensions
  
#### Regular Logs
```csharp
Dbug.Log(msg);
Dbug.Warning(msg);
Dbug.Error(msg);
```
#### Colored Logs
```csharp
Dbug.Red(msg);
Dbug.Orange(msg);
Dbug.Yellow(msg);
Dbug.Green(msg);
Dbug.Blue(msg);
Dbug.Indigo(msg);
Dbug.Violet(msg);
```
#### Stylized Logs
```csharp
Dbug.Bold(msg);
Dbug.Italic(msg);
Dbug.Underline(msg);
Dbug.Strikethrough(msg);
```
```csharp
Dbug.Emphasis(msg);
```

#### 🍦Chose your flavor.
```csharp
Dbug.MyLog(msg, #FFFFFF, false, false, false, false);
```
`msg, #hexcolor, bold, italic, underline, strikethrough`
</details>

<details>
<summary>📗DbugDiagnostic.cs</summary>
  
---

- When on a GameObject (within the scene): 
- Cycles through `Dbug.Log`



</details>

<!-- Start Whitespace /-->
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
<!-- End Whitespace /-->

<!-- Centered bottom image with scaling -->
<p align="center">
  <img src="https://github.com/SpawnCampGames/Documentation/blob/main/gfx/SpawnCampGames_DOC.png" width="300" alt="SpawnCampGames">
</p>
