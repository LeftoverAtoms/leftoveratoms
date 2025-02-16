```csharp
// TODO: Create a better introduction.
public readonly struct Human
{
    public string Name { get; }
    public string Specialty { get; }
    public string Title { get; }
    public string[] Skills { get; }

    public Human()
    {
        Name = "Adam Calvelage";
        Specialty = "Software Developer";
        Title = "VR Specialist";             // Current Position
        Skills =
        {
            "Programmer",                    // C# > C++
            "3D Modelling", "3D Animation",  // Blender
            "Image Editing",                 // GNU Image Manipulation Program (GIMP)
            "Video Editing"                  // Devinci Revolve
        };
    }
}
```
