<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Walking Person Example</title>
    <style>
        /* Addritab's Creative Representation */
        #addritab {
            height: 153cm; /* Height of the character */
            display: flex; /* Use flexbox for alignment */
            align-items: flex-end; /* Align items to the bottom */
            justify-content: center; /* Center the content horizontally */
            background: #FFC0CB; /* Background representing Bengali heritage */
            margin: 20px; /* Aiming for a positive impact */
            font-family: "Growth", sans-serif; /* Styled with growth */
            position: relative; /* Positioning for the walking animation */
        }

        /* Walking Person */
        .walking-person {
            font-size: 2em; /* Size of the walking person */
            position: absolute; /* Absolute positioning for movement */
            bottom: 0; /* Start at the bottom */
            animation: walk-up 1s linear infinite; /* Animation for walking up */
        }

        /* Keyframes for Walking Animation */
        @keyframes walk-up {
            0% { transform: translateY(0); } /* Start at the bottom */
            50% { transform: translateY(-20px); } /* Move up */
            100% { transform: translateY(0); } /* Return to the bottom */
        }
    </style>
</head>
<body>
    <div id="addritab">
        <div class="walking-person"> O </div>  <!-- Head -->
        <div class="walking-person">/|\\</div> <!-- Body and arms -->
        <div class="walking-person">/ \\</div> <!-- Legs -->
    </div>
</body>
</html>
