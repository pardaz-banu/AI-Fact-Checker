# AI-Fact-Checker

This project uses the Google Gemini API with the Google Search grounding tool enabled. The key feature is its ability to take any user-submitted claim (like a news headline or a statement) and use real-time Google Search results to provide a grounded, cited answer, which is far more impressive than a simple chatbot.
<br>

This solution will be implemented as a single, fully-responsive HTML file using Tailwind CSS and modern JavaScript to keep the setup minimal and focused on the AI functionality.

<br>
<ul>
  <li>A clean, responsive UI styled with Tailwind CSS (which loads via CDN).</li>

  <li>JavaScript logic to capture the user's claim and call the Gemini API. </li>

  <li>Google Search Grounding is enabled in the API payload (tools: [{ "google_search": {} }]).</li>

  <li>Error Handling and Loading Indicators for a polished user experience.</li>

  <li>Source Attribution, extracting the groundingAttributions from the API response to display the title and link of the web sources used to generate the answer.</li>
</ul>
