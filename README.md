# Spotify Songs Dashboard

## Project Overview

This project presents a comprehensive analysis of Spotify songs using Power BI, embedded within a phone mockup to enhance the user experience. The dashboard is designed with interactive elements and dynamic visuals to help users explore and understand the data effectively. 

The dashboard includes:
- **Home (1st Dashboard)**
- **Chart(2nd Dashboard)**
- **Filter Pop-up**

### Features

1. **Home (1st Dashboard)**
   - **Track Name and Sum of Streams**: A bar chart displaying the sum of streams for each track.
   - **Song Details**: A KPI chart showcasing the song name, artist name, sum of streams, release date, danceability percentage, speechiness percentage, liveness percentage, and the number of Spotify playlists the song is in.
   - **Dynamic Music Cover**: An HTML visual displaying the album cover image dynamically based on the data source link.

2. **Chart(2nd Dashboard)**
   - **Average Stream per Year**: A comparison of the average streams per year with the selected song's performance, color-coded to indicate whether the song is performing above or below average.
   - **Date-wise Song Streams**: A line chart showing the streams of songs over time.
   - **Energy Percentage**: A custom chart (Deneb Unichart) depicting the energy percentage of songs.
   - **Heat Map**: A heat map similar to GitHub’s, displaying the distribution of streams.

3. **Filter Pop-up**
   - **Slicers for Filtering**: A dedicated section with slicers to filter the data dynamically.
   - **Return Button**: A button to close the filter pop-up and return to the main dashboard view.

## Screenshots

### Home (1st Dashboard)
![Home Dashboard](images/home_dashboard.png)

### 2nd Dashboard
![2nd Dashboard](images/second_dashboard.png)

### Filter Pop-up
![Filter Pop-up](images/filter_popup.png)

## Installation and Usage

1. **Download the .pbix File**: Clone the repository and download the Power BI file (`Spotify Analysis.pbix`).

   ```bash
   git clone https://github.com/jyotirmaya16/Spotify Analysis.pbix
   ```

2. **Open in Power BI Desktop**: Open the downloaded `.pbix` file in Power BI Desktop.

3. **Interact with the Dashboard**:
   - Navigate through different dashboards using the Home, 2nd Dashboard, and Filter buttons.
   - Use the slicers in the Filter pop-up to dynamically filter the data.
   - Click the return button to close the Filter pop-up and return to the main view.

## Data Source

The data used in this project is sourced from Spotify. It includes various attributes such as track name, artist name, stream count, release date, danceability percentage, speechiness percentage, liveness percentage, and the number of playlists featuring each song.

## Custom Visuals

- **Dynamic Music Cover**: Implemented using an HTML visual to display album covers based on the provided data source links.
- **Energy Percentage Chart**: A custom chart built using Deneb Unichart for advanced visual representation.

## Contact

For any questions or suggestions, feel free to reach out:

- **Name**: Your Name
- **Email**: your.email@example.com
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/yourprofile)
- **GitHub**: [Your GitHub Profile](https://github.com/yourusername)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
