# Meet in @@webclient (Video Conferencing)

The Meet feature enables real-time video conferencing directly within the system, allowing users to initiate and participate in online meetings without leaving their working context. It is designed to support immediate communication and collaboration across teams by integrating video meetings into the environments where work is already managed.

Meet is available within Groups and can also be initiated from business-related records, including Cases, Activities, Service Activities and Marketing Activities.

This allows discussions to be started in direct relation to ongoing work, reducing the need to switch between tools and ensuring that communication remains context-aware.

The feature provides a unified video conferencing experience with the following capabilities:

- **Instant meeting initiation** <br>
  Any member of a group or participant in a supported record can start a meeting without prior scheduling.

- **Integrated meeting environment** <br>
  Meetings open in a dedicated video conferencing page and are connected to system notifications and chat.

- **Participation through chat notifications** <br>
  When a meeting starts, a system message is posted in the related chat, allowing participants to join directly.
  
- **Audio and video readiness** <br>
  Camera and microphone are available by default for all participants, enabling immediate interaction.

- **Recording functionality** <br>
  Meetings can be recorded, with recordings stored and made available for download after the session.
  
- **Automatic file management**<br>
  Recordings are saved in the corresponding Files section, with system-generated names based on date and time.

## Getting Started

### Start a meeting from a Group

_You are the initiating participant_

1. From within the Group, navigate to tab **Meet** and click on. it <br>
   An informative page opens.
   
2. Click on the button **"Start Meeting**".<br>
   A lobby page opens. It contains all group members.
   
3. Select the participating members.<br>
   The host member - you - is preselected and cannot be unchecked.
   
4. Click **"Start"**.<br>
   The video conferencing page opens and the meeting starts immediately.

The **video conferencing page** provides the active meeting environment where participants communicate in real time. It includes standard meeting controls, such as:

- Audio and video management
- Screen or content sharing
- Environment and layout settings
- Meeting recording controls

These controls allow participants to interact, present, and manage the meeting as it progresses.
   
> [!NOTE]
>  When a meeting is started, the system **notifies** participants through multiple channels:<br>
> 🔔 A system comment is posted in the group's chat: "_The meeting has started. Click **Join meeting** to participate._", where "Join meeting" is a link.<br>
> 🔔 A notification appears in the **Notifications** panel (Bell icon) and is marked as unread.<br>
> 🔔 A red toaster pops up in the bottom-right corner of the screen (for 10s). <br> 
> 🔔 A melody is played. It will stop if you click on the red toaster, or after 10 seconds.

### Join a meeting from a Group

_You are simply a participant_

**Variant A** - Join an ongoing meeting using the entry points in the NOTE<br>
1. Click on the red toaster, or the notification, or the link in the system comment - the system takes you to the lobby page.
2. Click **Join meeting** to enter the ongoing meeting.

**Variant B** - Join an ongoing meeting from the Group <br>
If you have missed the notifications you can:<be>
1. Go to tab Meet
2. Click **Join meeting** to enter the ongoing meeting.<br>
   The conferencing page opens, and you can see what is being shared and participate.

### Start a meeting from a record

You can initiate a meeting from the following records:
- Case  
- Activity  
- Service Activity  
- Marketing Activity  

1. Open the desired record.  
2. Open the main menu (three vertical dots in the top-right corner of the form).  
3. Select option **Meet**.  
   A side panel opens with the Meet initial page - _Start a new meeting_..  
4. Click **Start meeting**.  
   The meeting lobby page opens and displays the list of potential participants.  
5. Select/deselect the participants.  
6. Click **Start**.  
   The video conferencing page opens and the meeting starts.

### Join a meeting from a record

When a meeting is started, the system notifies participants through the mentioned channels (see Note above). The system message is posted in the related Discuss panel of the record.<br>

From within the record (Case, Activity, Service Activity, or Marketing Activity)

1. Join the meeting using any of the available entry points:
   - Click **Join meeting** in the chat message.  
   - Click on the notification from the **Notifications** panel. 
   - Click the red toaster.   
2. The meeting lobby page opens.  
3. Click **Join meeting** to enter the ongoing meeting.

*For rules about Participants, see Configuration.

### Record a meeting

1. In the video conferencing page, locate the recording control - a round button - and click on it.<br>
   A confirmation pop-up appears.<br>
2. Click **Start recording**.<br>  
   The system begins recording the meeting.<br>
💡 Two  toasters notify that a Recording is being prepared and a Link is generated.<br>
💡 A voice confirms that "Recording is on".<br>

To stop recording, click **Stop recording** - a square button. Confirm.<br> 
💡 A voice confirms that "Recording has stopped".<br>

The recording is available for download immediately after the meeting and is saved in the **Files** of the Group and the record. The file name includes the exact date and time of the meeting.

## Configuration

The availability of video conferencing features is **License-based**:

- **X19 – Basic**
  - Meetings are available for internal users only  
  - Recording is not available  

- **X20 – Advanced**
  - Meetings are available for both internal and external users  
  - Recording is available and can be initiated by internal users  


> [!IMPORTANT]
> Potential **Participants** in meetins are determined based on the context of the record.
> - A meeting from a Case calls participants who are Tagged at least, or have set higher follow level (Following, Favorite) for the record.<br>
> - A meeting from an Activity/Service Activity/Marketing Activity needs users explicitly listed as participants (panel "Participants".<br>
> - A meeting from a Group needs only its Group Members.

## Concepts

### Recording lifecycle

Meeting recordings are automatically processed and made available for download immediately after the meeting ends. They are stored in the **Files** section of the related group or record. The File is actually an URL address from which to download the recording. The recordings are in fact stored within the provider of the videoconferencing service "Jitsi.org"

Each recording is assigned a system-generated name that includes the exact date and time of the meeting.

Recordings are available for download for a limited time only:
- The download link remains active for 24 hours  
- After this period, the recording is automatically deleted and can no longer be accessed  

