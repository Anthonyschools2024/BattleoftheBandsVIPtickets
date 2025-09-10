Resistance Jam: VIP Event Page

This project is a single-page, fully responsive website specifically designed for the sale of VIP tickets to the "Resistance Jam" event. The page serves as an exclusive, customer-facing portal, providing details on VIP perks and a direct path to purchase, all presented within an immersive sci-fi/rebel theme.
✨ VIP Features

    Exclusive VIP Content: The page is tailored to a VIP audience, with a "VIP High Command" theme. It details exclusive perks such as access to the "High Command Lounge," unlimited visits to "The Spice Mines Dab Bar," and "Priority Access Credentials."

    Clear Pricing: The VIP ticket price of $25 (25 Galactic Credits) is clearly stated in both the description and on the purchase form itself.

    Thematic Design: A dark, space-themed design using custom fonts (Orbitron, Roboto) and a color scheme that evokes a "rebel alliance" feel.

    Clear Event Details: The "Mission Briefing" section prominently displays the event date, time, and location.

    Interactive Map Button: A glowing, themed button provides a direct link to the event location on Google Maps for easy navigation.

    Streamlined VIP Ticket Purchasing: The page's sole purpose is to guide users to purchase a VIP pass through a simple and clear form.

⚙️ How It Works

The website is a self-contained index.html file. Its core interactive element is the "Secure VIP High Command Pass" form, which uses a two-step process:

    Data Collection: The user fills in their Name, Email, and Phone Number. This information is submitted to a Formspree endpoint (https://formspree.io/f/mzzaovzb) for your records.

    Payment Redirection: Custom JavaScript handles the form submission.

        Upon a successful submission to Formspree, the script displays a confirmation message ("Info received! Redirecting...").

        It then automatically redirects the user to the specific VIP PayPal payment link (https://www.paypal.com/ncp/payment/KUAYKDKJVCL8W) to securely complete their purchase.

        Error messages are in place to handle any network or submission issues.

🛠️ Technologies Used

    HTML5: For the core structure of the webpage.

    Tailwind CSS: A utility-first CSS framework used for all styling, loaded via a CDN link.

    Custom CSS: Inline CSS is used within <style> tags for the background, font definitions, and custom button styles (including the hover glow effect).

    Google Fonts: For the unique, thematic typography.

    Vanilla JavaScript: For handling the ticket form submission, displaying status messages, and managing the redirect to the payment page.

🚀 How to Use

No complex setup is required. Simply open the index.html file in any modern web browser to view and interact with the page.