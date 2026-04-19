```csharp id="p7xk21"
using System;

class Jay
{
    static void Main()
    {
        Console.WriteLine("Hey, I'm Jay");
        Console.WriteLine("i make games. sometimes they work, sometimes they fight back.\n");

        Projects();
        Doing();
        Tools();
        Philosophy();
        CurrentState();
        Outro();
    }

    static void Projects()
    {
        Console.WriteLine("things i've made / making:\n");

        Console.WriteLine("mobile puzzle game -> simple idea, surprisingly tricky");
        Console.WriteLine("endless runner -> speed, movement, don't crash");
        Console.WriteLine("platformers (2d + 3d) -> jump, break, fix, repeat\n");

        Console.WriteLine("// most of this lives in my repos\n");
    }

    static void Doing()
    {
        Console.WriteLine("what i'm usually doing:\n");

        string[] stuff = {
            "messing with gameplay feel",
            "trying ideas that sound dumb until they aren’t",
            "starting projects... finishing some of them"
        };

        foreach (var s in stuff)
            Console.WriteLine("- " + s);

        Console.WriteLine();
    }

    static void Tools()
    {
        Console.WriteLine("tools:\n");
        Console.WriteLine("unity + c#");
        Console.WriteLine("google, trial & error, and a bit of patience\n");
    }

    static void Philosophy()
    {
        Console.WriteLine("what i care about:\n");

        Console.WriteLine("> games that feel good to play");
        Console.WriteLine("> simple mechanics done right");
        Console.WriteLine("> a little bit of weirdness\n");
    }

    static void CurrentState()
    {
        Console.WriteLine("right now:\n");
        Console.WriteLine("trying to actually finish something properly");
        Console.WriteLine("not just another 'this could be cool' project\n");
    }

    static void Outro()
    {
        Console.WriteLine("if you're here:\n");
        Console.WriteLine("look around, try stuff, break things");
        Console.WriteLine("// that's kinda the point");
    }
}
```


<!---
JaySawant2707/JaySawant2707 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
