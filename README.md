# CS193-Project
**GOAL
**
My alternative to Purdue's website is a terminal-based program where users can select and save their interests as event categories. It retrieves events from Purdue's public API and filters that information to display a short list matching the user's selected categories when the program opens. It will show the key details and a link to each event.

**MVP**
On the terminal,
- Select and save interests.
- Retrieve events from Purdue’s public API.
- When the program opens, display a short list matching those interests.
- Show key details and a link to each event.

**Future Plans**
- Phone home-screen widget.
- Automatic refreshing/updating.
- Three user-assigned interest priority levels, with matching events ordered accordingly.
- Optional phone notifications for selected categories.

**Tech Stack**
I will use the Java language and request Purdue's event data (source: https://events.purdue.edu/api/2/events) using Java's built-in HttpClient. I will use Gson to read the returned JSON, and I will use a .txt file and Java's file tools to save the user's selected categories. I will use Java's Scanner to read the user's category choices.
