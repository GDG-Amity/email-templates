# GDG On Campus Amity University Noida - Email Templates

This folder contains HTML email templates designed to match the Google Developer Groups branding and style, specifically customized for GDG On Campus Amity University Noida.

## Templates Available

### 1. `application-thank-you.html`
A template for thanking applicants and providing next steps while they wait for results.

**Template Variables:**
- `{{applicant_name}}` - Applicant's name
- `{{review_timeframe}}` - Number of days for review process
- `{{whatsapp_group_url}}` - WhatsApp group invitation link
- `{{member_count}}`, `{{event_count}}`, `{{project_count}}` - Community statistics

### 2. `welcome-community.html`
A template for welcoming new members to the GDG community.

**Template Variables:**
- `{{member_name}}` - New member's name
- `{{whatsapp_group_url}}` - WhatsApp group link
- `{{discord_url}}` - Discord community link
- `{{linkedin_url}}`, `{{instagram_url}}`, `{{twitter_url}}`, `{{youtube_url}}` - Social media links
- `{{unsubscribe_url}}` - Unsubscribe link

### 3. `event-announcement.html`
A template for announcing upcoming GDG events to community members.

**Template Variables:**
- `{{recipient_name}}` - Recipient's name
- `{{event_title}}` - Event title
- `{{event_subtitle}}` - Event subtitle/description
- `{{event_date}}` - Event date
- `{{event_time}}` - Event time
- `{{event_location}}` - Event venue
- `{{event_price}}` - Entry fee (e.g., "Free", "$10")
- `{{learning_point_1}}`, `{{learning_point_2}}`, `{{learning_point_3}}`, `{{learning_point_4}}` - Key learning points
- `{{speaker_1_name}}`, `{{speaker_1_title}}`, `{{speaker_1_bio}}`, `{{speaker_1_initial}}` - First speaker details
- `{{speaker_2_name}}`, `{{speaker_2_title}}`, `{{speaker_2_bio}}`, `{{speaker_2_initial}}` - Second speaker details
- `{{registration_url}}` - Registration/RSVP link
- `{{instagram_url}}`, `{{linkedin_url}}`, `{{twitter_url}}`, `{{youtube_url}}` - Social media links
- `{{unsubscribe_url}}` - Unsubscribe link

### 4. `gdg-chapter-status-template.html`
The original template for communicating chapter status updates to organizers.

**Template Variables:**
- `{{name}}` - Recipient's name
- `{{event_platform_url}}` - Link to event platform
- `{{discussion_author_1}}`, `{{discussion_author_2}}`, `{{discussion_author_3}}` - Discussion authors
- `{{discussion_title_1}}`, `{{discussion_title_2}}`, `{{discussion_title_3}}` - Discussion titles
- `{{discussion_time_1}}`, `{{discussion_time_2}}`, `{{discussion_time_3}}` - Discussion timestamps

## Design Features

All templates include:
- **GDG On Campus Branding**: Customized for Amity University Noida
- **Google Brand Colors**: Official Google blue, green, yellow, and red
- **Responsive Design**: Mobile-friendly layouts
- **Professional Typography**: Google Sans font family
- **Interactive Elements**: Hover effects and call-to-action buttons
- **Accessibility**: Good color contrast and semantic HTML
- **Footer Link**: All templates link to https://gdgamity.tech

## Organizer Information

Templates feature:
- **Rajat Rajput** as the primary organizer
- **GDG On Campus Amity University Noida** branding
- Consistent messaging and tone

## Usage Instructions

1. Choose the appropriate template for your use case
2. Replace all `{{variable}}` placeholders with actual content
3. Test the email in different email clients
4. Customize colors and styling if needed for specific events

## Email Client Compatibility

These templates are optimized for:
- Gmail
- Outlook (2016+)
- Apple Mail
- Yahoo Mail
- Mobile email apps

## Template Use Cases

- **Application Thank You**: Send immediately after someone applies to join
- **Welcome Community**: Send when someone is accepted and joins
- **Event Announcement**: Send for upcoming workshops, talks, hackathons
- **Chapter Status**: Administrative communications for organizers

## Testing

Before sending emails:
1. Test on desktop and mobile devices
2. Check all links are working (especially WhatsApp and registration links)
3. Verify all template variables are replaced
4. Test with different email clients if possible
