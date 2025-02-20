# Porsche Racetrack Lap Logger

This project is a simple web application for logging lap times on a Porsche racetrack. It allows users to input the car name, driver email, and lap time (in minutes, seconds, and hundredths), along with the track condition (dry or wet). The data is saved to the browser’s localStorage, and can be retrieved and displayed on demand.

## Features

- **Lap Time Input**: Three separate fields for minutes, seconds, and hundredths of a second.
- **Car & Driver Info**: Collects the car name and driver’s email address.
- **Track Condition**: Choose between “dry” or “wet” track.
- **Validation**: Checks for correct email format and numeric values.
- **Local Storage**: Saves entries so they persist across page reloads.
- **Toggle Display**: Show or hide saved lap times on demand.
- **Success Feedback**: Displays a success image and message upon successful submission.
- **Console Logging**: Each data entry is logged to the browser’s console for debugging.

## How to Use

1. **Open index.html** in your web browser (ensure you have jQuery or an internet connection if using a CDN).
2. **Fill out the form** with:
    - Car name
    - Driver email
    - Lap time (in minutes, seconds, hundredths)
    - Track condition
3. **Submit** by clicking “Saada.” If validation is successful, a success image and message will appear, and the entry will be saved.
4. **View saved entries** by clicking “Näita/Peida Salvestatud Tulemused.”

## License

This project is provided as-is for educational or demonstration purposes. Feel free to modify it according to your needs.
EOF

