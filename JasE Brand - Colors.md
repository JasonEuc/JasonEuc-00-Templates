


    color: #F15524 !important; /* Flag Orange */
    background-color: #FFF9E6; /* Very light tint of Old Gold for background */
    color: #041E42; /* Obsidian Blue "Ink" */
    color: #00AFB5 !important; /* Turquoise */

    color: #3C3C3C; /* Anthracite */
    code color: color: #c8c8c8 !important;

    background-color: #f8f9fa;

    /* Note - Safety Blue (General Information) */
.markdown-alert-note {
    border-left-color: #002664 !important; /* ANSI Safety Blue */
    background-color: #e3f2fd !important;
    color: #002664 !important;
}

/* Tip - Professional Green (Best Practice) */
.markdown-alert-tip {
    border-left-color: #1b5e20 !important; /* Darker Green Border */
    background-color: #e8f5e9 !important; /* Lighter Green Background */
    color: #1b5e20 !important;
}

/* Important - Visual Purple (Critical Technical Info) */
.markdown-alert-important {
    border-left-color: #4a148c !important; /* Darker Purple Border */
    background-color: #f3e5f5 !important; /* Lighter Purple Background */
    color: #4a148c !important;
}

/* Warning - Safety Orange (Moderate Hazard) */
.markdown-alert-warning {
    border-left-color: #FF7900 !important; /* ANSI Safety Orange */
    background-color: #ffe4cc !important;
    color: #b35500 !important;
}

/* Caution - Safety Red (High Hazard / Danger) */
.markdown-alert-caution {
    border-left-color: #B71C1C !important; /* ANSI Safety Red */
    background-color: #ffebee !important;
    color: #B71C1C !important;
}

/* Horizontal Rule */
hr {
    border: none; 
    height: 1.5px; 
    background-color: #00AFB5 !important; /* Turquoise */ 
    margin: 16px 0 20px 0;


    .draft { background-color: #d6a946; color: #333; }
.approved { background-color: #00AFB5; color: #333; }
.confidential { background-color: #fad1db; color: #333333; border: 1px solid #333; }


/* --- Tables (The "Cramped" Fix) --- */
table {
    width: 100%;
    border-collapse: collapse;
    margin: 25px 0;
    font-size: 0.95em;
    font-family: Inter, sans-serif;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.05);
}

th, td {
    padding: 12px 15px; /* This adds the necessary breathing room */
    text-align: left;
    border-bottom: 1px solid #dddddd;
}

th {
    background-color: #00AFB5 !important; /* Turquoise */ 
    color: #ffffff;
    font-weight: 700;
    text-transform: uppercase;
    font-size: 0.85em;
    letter-spacing: 1px;
}

tr:nth-child(odd) {
    background-color: #e6f7f8; /* Subtle zebra striping for readability */
}

tr:nth-child(even) {
    background-color: #b3e7e9; /* Subtle zebra striping for readability */
}

/*tr:last-of-type {
    border-bottom: 2px solid #004990;
}*/

tr:hover {
    background-color: #fcddd3; /* Highlights the row for easier tracking */
}