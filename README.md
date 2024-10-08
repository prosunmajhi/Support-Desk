<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Request Form with Ant Animation</title>
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
 
 
 
 body {
            background-color: #e9ecef; /* Light gray background */
            display: flex;
            justify-content: center;
            align-items: flex-start; 
            min-height: 100vh; 
            margin: 0;
        }
		
		
.wrapper {
	 display: flex;
	 width: 100%;
     max-width: 600px;
	 align-items: center;
	 justify-content: center;
	/* Old browsers */
	 background: -moz-linear-gradient(45deg, #7ae298 0%, #9af282 100%);
	/* FF3.6-15 */
	 background: -webkit-linear-gradient(45deg, #7ae298 0%, #9af282 100%);
	/* Chrome10-25,Safari5.1-6 */
	 background: linear-gradient(45deg, #7ae298 0%, #9af282 100%);
}
 .cube {
	 position: relative;
	 width: 650px;
	 height: 600px;
	 background-color: #fff;
	 align-items: center;
	 justify-content: center;
}
 .ants {
	 fill: black;
	 width: 25px;
	 height: 25px;
	 position: absolute;
}
 #ant1 {
	 left: 50%;
	 bottom: -60%;
	 animation: ant-1-animation 8s infinite;
}
 #ant2 {
	 left: 0;
	 bottom: -50%;
	 animation: ant-2-animation 9s infinite;
}
 #ant3 {
	 left: 100%;
	 bottom: -70%;
	 animation: ant-3-animation 12s infinite;
	 animation-delay: 1s;
}
 #ant4 {
	 left: 0;
	 bottom: -50%;
	 animation: ant-2-animation 12s infinite;
	 animation-delay: 3s;
}
 @keyframes ant-1-animation {
	 0% {
		 left: 50%;
		 bottom: -60%;
	}
	 10% {
		 left: 50%;
		 bottom: 5%;
		 transform: rotate(0deg);
	}
	 12% {
		 left: 50%;
		 bottom: 5%;
		 transform: rotate(-90deg);
	}
	 18% {
		 transform: rotate(-90deg);
	}
	 20% {
		 left: 5%;
		 bottom: 5%;
		 transform: rotate(-90deg);
	}
	 22% {
		 transform: rotate(0);
	}
	 32% {
		 transform: rotate(0);
	}
	 38% {
		 left: 5%;
		 bottom: 87%;
		 transform: rotate(90deg);
	}
	 50% {
		 left: 90%;
		 bottom: 87%;
		 transform: rotate(90deg);
	}
	 55% {
		 left: 90%;
		 bottom: 87%;
		 transform: rotate(230deg);
	}
	 72% {
		 left: 5%;
		 bottom: 5%;
		 transform: rotate(230deg);
	}
	 78% {
		 left: 5%;
		 bottom: 5%;
		 transform: rotate(90deg);
	}
	 85% {
		 left: 50%;
		 bottom: 5%;
		 transform: rotate(90deg);
	}
	 90% {
		 left: 50%;
		 bottom: 5%;
		 transform: rotate(180deg);
	}
	 100% {
		 left: 50%;
		 bottom: -60%;
		 transform: rotate(180deg);
	}
}
 @keyframes ant-2-animation {
	 0% {
		 left: 0;
		 bottom: -50%;
		 transform: rotate(45deg);
	}
	 15% {
		 left: 50%;
		 bottom: 5%;
		 transform: rotate(45deg);
	}
	 18% {
		 left: 50%;
		 bottom: 5%;
		 transform: rotate(90deg);
	}
	 28% {
		 left: 85%;
		 bottom: 5%;
		 transform: rotate(90deg);
	}
	 30% {
		 left: 85%;
		 bottom: 5%;
		 transform: rotate(0deg);
	}
	 40% {
		 left: 85%;
		 bottom: 85%;
		 transform: rotate(0deg);
	}
	 48% {
		 left: 85%;
		 bottom: 85%;
		 transform: rotate(-90deg);
	}
	 58% {
		 left: 5%;
		 bottom: 85%;
		 transform: rotate(-90deg);
	}
	 68% {
		 left: 5%;
		 bottom: 85%;
		 transform: rotate(-180deg);
	}
	 79% {
		 left: 5%;
		 bottom: 5%;
		 transform: rotate(-180deg);
	}
	 81% {
		 left: 5%;
		 bottom: 5%;
		 transform: rotate(-270deg);
	}
	 88% {
		 left: 50%;
		 bottom: 5%;
		 transform: rotate(-270deg);
	}
	 90% {
		 left: 50%;
		 bottom: 5%;
		 transform: rotate(-140deg);
	}
	 100% {
		 left: 0%;
		 bottom: -50%;
		 transform: rotate(-140deg);
	}
}
 @keyframes ant-3-animation {
  0% {
    left: 100%;
    bottom: -70%;
    transform: rotate(-45deg);
  }
  15% {
    left: 50%;
    bottom: -15%;
    transform: rotate(-45deg);
  }
  18% {
    left: 50%;
    bottom: -15%;
    transform: rotate(-90deg);
  }
  28% {
    left: -10%;
    bottom: -15%;
    transform: rotate(-90deg);
  }
  30% {
    left: -10%;
    bottom: -15%;
    transform: rotate(0deg);
  }
  45% {
    left: -10%;
    bottom: 105%;
    transform: rotate(0deg);
  }
  48% {
    left: -10%;
    bottom: 105%;
    transform: rotate(90deg);
  }
  58% {
    left: 105%;
    bottom: 105%;
    transform: rotate(90deg);
  }
  60% {
    left: 105%;
    bottom: 105%;
    transform: rotate(180deg);
  }
  75% {
    left: 105%;
    bottom: -15%;
    transform: rotate(180deg);
  }
  81% {
    left: 105%;
    bottom: -15%;
    transform: rotate(270deg);
  }
  88% {
    left: 50%;
    bottom: -15%;
    transform: rotate(270deg);
  }
  90% {
    left: 50%;
    bottom: -15%;
    transform: rotate(180deg);
  }
  92% {
    left: 50%;
    bottom: -15%;
    transform: rotate(130deg);
  }
  100% {
    left: 100%;
    bottom: -70%;
    transform: rotate(130deg);
  }
}

 
        .form-container {
            background-color: rgba(255, 255, 255, 0.9); 
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
            width: 100%;
            max-width: 600px; 
            box-sizing: border-box;
            margin-top: 20px; 
        }
        h2 {
            color: #dc3545; /* Heartbeat color (red) */
            text-align: center;
            margin-bottom: 10px;
            font-size: 2rem;
            animation: heartbeat 1.5s infinite; /* Animation for heartbeat effect */
        }
        @keyframes heartbeat {
            0%, 20%, 40%, 60%, 100% {
                transform: scale(1);
            }
            10% {
                transform: scale(1.1);
            }
            30% {
                transform: scale(1.05);
            }
            50% {
                transform: scale(1.1);
            }
            70% {
                transform: scale(1.05);
            }
        }
        .neon {
            display: block;
            margin: 0 auto;
            width: 100%;
            max-width: 600px;
            height: 50px;
            filter: drop-shadow(0 0 5px rgba(220, 53, 69, 0.7))
                    drop-shadow(0 0 10px rgba(220, 53, 69, 0.7))
                    drop-shadow(0 0 20px rgba(220, 53, 69, 0.7));
        }
        .form-control {
            border: 1px solid #ced4da;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); 
            transition: box-shadow 0.3s ease, transform 0.3s ease;
        }
        .form-control:focus {
            box-shadow: 0 0 5px rgba(0, 123, 255, 0.5);
            border-color: #007bff;
        }
        .progress {
            display: none;
            text-align: center;
            margin: 10px 0;
        }

        /* Styles for screens 6.5 inches and below */
        @media (max-width: 414px) {
            .form-container {
                padding: 15px;
                box-shadow: 0 8px 30px rgba(0, 0, 0, 0.15);
            }
            h2 {
                font-size: 1.5rem;
            }
            input[type="submit"] {
                font-size: 1.1rem;
            }
        

    </style>
</head>
<body>
    <div class="wrapper">
  <div class="cube">
    <svg id="ant1" class="ants" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.39 53.12"><title>ant</title><path d="M539.22,398.8a20.17,20.17,0,0,0,3-10.91,14,14,0,0,1,6.22-12.12c.58-.41.56-1.79.6-2.74,0-.18-1-.44-1.53-.61a10.21,10.21,0,0,1-2.52-.74,3.21,3.21,0,0,0-3.17-.18,16.22,16.22,0,0,1-5,.34c-.4,0-.8-.54-1.2-.83l.17-.32c.3.09.6.16.89.27a4.36,4.36,0,0,0,4.08-.16c1.9-1.12,3.92-1.5,5.88.08a8.9,8.9,0,0,0,1.79.86c.43-2.45.07-4.19-1.94-5.61-1.13-.8-1.77-2.3-2.59-3.51a4.82,4.82,0,0,1-.58-1.2c-.89-2.69-3.22-3.93-5.38-5.33a8.47,8.47,0,0,1-.86-.64c-.09-.07-.11-.23-.32-.71.74.37,1.22.58,1.67.83,1.32.74,2.66,1.45,3.92,2.28a3.13,3.13,0,0,1,1,1.45,13.54,13.54,0,0,0,4.09,6l1.88-2.86c-2.65-.24-3.22-1.08-2.51-3.8.22-.86.56-1.68.91-2.71-1.3-.4-2.55-.85-3.83-1.17a3,3,0,0,1-2.21-1.94c-1-2.31-1.82-4.69-3.92-6.3-.13-.1-.11-.38.08-.83.42.31,1,.52,1.24.94,1,1.66,1.92,3.41,3,5.06a5.58,5.58,0,0,0,1.66,1.73,19.86,19.86,0,0,0,2.81,1.25c1,.44,2,.88,3.13.07a1.68,1.68,0,0,1,1.42-.13c1.29.57,2.27-.17,3.4-.52,2.45-.75,4.18-2,4.47-4.76a3.2,3.2,0,0,1,2.11-2.53,3.33,3.33,0,0,1-.26.82,9.36,9.36,0,0,0-2,5,1.67,1.67,0,0,1-1.59,1.65c-1.33.26-2.62.7-3.87,1a38.19,38.19,0,0,1,1.09,4c.36,2.31-.35,3.06-2.8,3l1.91,3a46.1,46.1,0,0,0,3-4.59c.74-1.48,1.2-2.93,3-3.58,1.38-.49,2.57-1.55,4.06-2.15a2.18,2.18,0,0,1-.39.65,8.37,8.37,0,0,1-1.66,1.13c-2.62,1.17-3.78,3.5-4.92,5.91a11.72,11.72,0,0,1-2.19,3.19c-2.42,2.44-2.18,2.73-2,5.77a7.21,7.21,0,0,0,1.52-.72c1.88-1.54,3.86-1.32,5.75-.2a4.4,4.4,0,0,0,4.45.1c.2-.09.41-.15.61-.22l.26.36c-.55.34-1.1,1-1.66,1-1.8,0-3.66.35-5.35-.72a2.33,2.33,0,0,0-1.56.07c-1.22.33-2.43.73-3.63,1.13a1.85,1.85,0,0,0-.86.47c-.28.35.41,3,.78,3.36.79.72,1.59,1.43,2.36,2.18,2.78,2.68,3.25,6.16,3.36,9.75a22.41,22.41,0,0,0,2.87,10.44,1.74,1.74,0,0,1-1.64-1.54c-.86-3.41-2.14-6.72-2.29-10.31-.14-3.25-.56-4.16-1.89-5.52a24.93,24.93,0,0,1-.17,4.45,12.52,12.52,0,0,1-1.68,4.17c-1.53,2.36-4.41,2.28-6-.05-1.85-2.67-2.05-5.66-1.53-8.76.06-.35.16-.69.25-1.07a6.81,6.81,0,0,0-2.94,5.69c-.17,3.81-1.31,7.38-2.26,11A2.54,2.54,0,0,1,539.22,398.8Z" transform="translate(-535.68 -345.68)"/></svg>
    <svg id="ant2" class="ants" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.39 53.12"><title>ant</title><path d="M539.22,398.8a20.17,20.17,0,0,0,3-10.91,14,14,0,0,1,6.22-12.12c.58-.41.56-1.79.6-2.74,0-.18-1-.44-1.53-.61a10.21,10.21,0,0,1-2.52-.74,3.21,3.21,0,0,0-3.17-.18,16.22,16.22,0,0,1-5,.34c-.4,0-.8-.54-1.2-.83l.17-.32c.3.09.6.16.89.27a4.36,4.36,0,0,0,4.08-.16c1.9-1.12,3.92-1.5,5.88.08a8.9,8.9,0,0,0,1.79.86c.43-2.45.07-4.19-1.94-5.61-1.13-.8-1.77-2.3-2.59-3.51a4.82,4.82,0,0,1-.58-1.2c-.89-2.69-3.22-3.93-5.38-5.33a8.47,8.47,0,0,1-.86-.64c-.09-.07-.11-.23-.32-.71.74.37,1.22.58,1.67.83,1.32.74,2.66,1.45,3.92,2.28a3.13,3.13,0,0,1,1,1.45,13.54,13.54,0,0,0,4.09,6l1.88-2.86c-2.65-.24-3.22-1.08-2.51-3.8.22-.86.56-1.68.91-2.71-1.3-.4-2.55-.85-3.83-1.17a3,3,0,0,1-2.21-1.94c-1-2.31-1.82-4.69-3.92-6.3-.13-.1-.11-.38.08-.83.42.31,1,.52,1.24.94,1,1.66,1.92,3.41,3,5.06a5.58,5.58,0,0,0,1.66,1.73,19.86,19.86,0,0,0,2.81,1.25c1,.44,2,.88,3.13.07a1.68,1.68,0,0,1,1.42-.13c1.29.57,2.27-.17,3.4-.52,2.45-.75,4.18-2,4.47-4.76a3.2,3.2,0,0,1,2.11-2.53,3.33,3.33,0,0,1-.26.82,9.36,9.36,0,0,0-2,5,1.67,1.67,0,0,1-1.59,1.65c-1.33.26-2.62.7-3.87,1a38.19,38.19,0,0,1,1.09,4c.36,2.31-.35,3.06-2.8,3l1.91,3a46.1,46.1,0,0,0,3-4.59c.74-1.48,1.2-2.93,3-3.58,1.38-.49,2.57-1.55,4.06-2.15a2.18,2.18,0,0,1-.39.65,8.37,8.37,0,0,1-1.66,1.13c-2.62,1.17-3.78,3.5-4.92,5.91a11.72,11.72,0,0,1-2.19,3.19c-2.42,2.44-2.18,2.73-2,5.77a7.21,7.21,0,0,0,1.52-.72c1.88-1.54,3.86-1.32,5.75-.2a4.4,4.4,0,0,0,4.45.1c.2-.09.41-.15.61-.22l.26.36c-.55.34-1.1,1-1.66,1-1.8,0-3.66.35-5.35-.72a2.33,2.33,0,0,0-1.56.07c-1.22.33-2.43.73-3.63,1.13a1.85,1.85,0,0,0-.86.47c-.28.35.41,3,.78,3.36.79.72,1.59,1.43,2.36,2.18,2.78,2.68,3.25,6.16,3.36,9.75a22.41,22.41,0,0,0,2.87,10.44,1.74,1.74,0,0,1-1.64-1.54c-.86-3.41-2.14-6.72-2.29-10.31-.14-3.25-.56-4.16-1.89-5.52a24.93,24.93,0,0,1-.17,4.45,12.52,12.52,0,0,1-1.68,4.17c-1.53,2.36-4.41,2.28-6-.05-1.85-2.67-2.05-5.66-1.53-8.76.06-.35.16-.69.25-1.07a6.81,6.81,0,0,0-2.94,5.69c-.17,3.81-1.31,7.38-2.26,11A2.54,2.54,0,0,1,539.22,398.8Z" transform="translate(-535.68 -345.68)"/></svg>
    <svg id="ant3" class="ants" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.39 53.12"><title>ant</title><path d="M539.22,398.8a20.17,20.17,0,0,0,3-10.91,14,14,0,0,1,6.22-12.12c.58-.41.56-1.79.6-2.74,0-.18-1-.44-1.53-.61a10.21,10.21,0,0,1-2.52-.74,3.21,3.21,0,0,0-3.17-.18,16.22,16.22,0,0,1-5,.34c-.4,0-.8-.54-1.2-.83l.17-.32c.3.09.6.16.89.27a4.36,4.36,0,0,0,4.08-.16c1.9-1.12,3.92-1.5,5.88.08a8.9,8.9,0,0,0,1.79.86c.43-2.45.07-4.19-1.94-5.61-1.13-.8-1.77-2.3-2.59-3.51a4.82,4.82,0,0,1-.58-1.2c-.89-2.69-3.22-3.93-5.38-5.33a8.47,8.47,0,0,1-.86-.64c-.09-.07-.11-.23-.32-.71.74.37,1.22.58,1.67.83,1.32.74,2.66,1.45,3.92,2.28a3.13,3.13,0,0,1,1,1.45,13.54,13.54,0,0,0,4.09,6l1.88-2.86c-2.65-.24-3.22-1.08-2.51-3.8.22-.86.56-1.68.91-2.71-1.3-.4-2.55-.85-3.83-1.17a3,3,0,0,1-2.21-1.94c-1-2.31-1.82-4.69-3.92-6.3-.13-.1-.11-.38.08-.83.42.31,1,.52,1.24.94,1,1.66,1.92,3.41,3,5.06a5.58,5.58,0,0,0,1.66,1.73,19.86,19.86,0,0,0,2.81,1.25c1,.44,2,.88,3.13.07a1.68,1.68,0,0,1,1.42-.13c1.29.57,2.27-.17,3.4-.52,2.45-.75,4.18-2,4.47-4.76a3.2,3.2,0,0,1,2.11-2.53,3.33,3.33,0,0,1-.26.82,9.36,9.36,0,0,0-2,5,1.67,1.67,0,0,1-1.59,1.65c-1.33.26-2.62.7-3.87,1a38.19,38.19,0,0,1,1.09,4c.36,2.31-.35,3.06-2.8,3l1.91,3a46.1,46.1,0,0,0,3-4.59c.74-1.48,1.2-2.93,3-3.58,1.38-.49,2.57-1.55,4.06-2.15a2.18,2.18,0,0,1-.39.65,8.37,8.37,0,0,1-1.66,1.13c-2.62,1.17-3.78,3.5-4.92,5.91a11.72,11.72,0,0,1-2.19,3.19c-2.42,2.44-2.18,2.73-2,5.77a7.21,7.21,0,0,0,1.52-.72c1.88-1.54,3.86-1.32,5.75-.2a4.4,4.4,0,0,0,4.45.1c.2-.09.41-.15.61-.22l.26.36c-.55.34-1.1,1-1.66,1-1.8,0-3.66.35-5.35-.72a2.33,2.33,0,0,0-1.56.07c-1.22.33-2.43.73-3.63,1.13a1.85,1.85,0,0,0-.86.47c-.28.35.41,3,.78,3.36.79.72,1.59,1.43,2.36,2.18,2.78,2.68,3.25,6.16,3.36,9.75a22.41,22.41,0,0,0,2.87,10.44,1.74,1.74,0,0,1-1.64-1.54c-.86-3.41-2.14-6.72-2.29-10.31-.14-3.25-.56-4.16-1.89-5.52a24.93,24.93,0,0,1-.17,4.45,12.52,12.52,0,0,1-1.68,4.17c-1.53,2.36-4.41,2.28-6-.05-1.85-2.67-2.05-5.66-1.53-8.76.06-.35.16-.69.25-1.07a6.81,6.81,0,0,0-2.94,5.69c-.17,3.81-1.31,7.38-2.26,11A2.54,2.54,0,0,1,539.22,398.8Z" transform="translate(-535.68 -345.68)"/></svg>
    <svg id="ant4" class="ants" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 29.39 53.12"><title>ant</title><path d="M539.22,398.8a20.17,20.17,0,0,0,3-10.91,14,14,0,0,1,6.22-12.12c.58-.41.56-1.79.6-2.74,0-.18-1-.44-1.53-.61a10.21,10.21,0,0,1-2.52-.74,3.21,3.21,0,0,0-3.17-.18,16.22,16.22,0,0,1-5,.34c-.4,0-.8-.54-1.2-.83l.17-.32c.3.09.6.16.89.27a4.36,4.36,0,0,0,4.08-.16c1.9-1.12,3.92-1.5,5.88.08a8.9,8.9,0,0,0,1.79.86c.43-2.45.07-4.19-1.94-5.61-1.13-.8-1.77-2.3-2.59-3.51a4.82,4.82,0,0,1-.58-1.2c-.89-2.69-3.22-3.93-5.38-5.33a8.47,8.47,0,0,1-.86-.64c-.09-.07-.11-.23-.32-.71.74.37,1.22.58,1.67.83,1.32.74,2.66,1.45,3.92,2.28a3.13,3.13,0,0,1,1,1.45,13.54,13.54,0,0,0,4.09,6l1.88-2.86c-2.65-.24-3.22-1.08-2.51-3.8.22-.86.56-1.68.91-2.71-1.3-.4-2.55-.85-3.83-1.17a3,3,0,0,1-2.21-1.94c-1-2.31-1.82-4.69-3.92-6.3-.13-.1-.11-.38.08-.83.42.31,1,.52,1.24.94,1,1.66,1.92,3.41,3,5.06a5.58,5.58,0,0,0,1.66,1.73,19.86,19.86,0,0,0,2.81,1.25c1,.44,2,.88,3.13.07a1.68,1.68,0,0,1,1.42-.13c1.29.57,2.27-.17,3.4-.52,2.45-.75,4.18-2,4.47-4.76a3.2,3.2,0,0,1,2.11-2.53,3.33,3.33,0,0,1-.26.82,9.36,9.36,0,0,0-2,5,1.67,1.67,0,0,1-1.59,1.65c-1.33.26-2.62.7-3.87,1a38.19,38.19,0,0,1,1.09,4c.36,2.31-.35,3.06-2.8,3l1.91,3a46.1,46.1,0,0,0,3-4.59c.74-1.48,1.2-2.93,3-3.58,1.38-.49,2.57-1.55,4.06-2.15a2.18,2.18,0,0,1-.39.65,8.37,8.37,0,0,1-1.66,1.13c-2.62,1.17-3.78,3.5-4.92,5.91a11.72,11.72,0,0,1-2.19,3.19c-2.42,2.44-2.18,2.73-2,5.77a7.21,7.21,0,0,0,1.52-.72c1.88-1.54,3.86-1.32,5.75-.2a4.4,4.4,0,0,0,4.45.1c.2-.09.41-.15.61-.22l.26.36c-.55.34-1.1,1-1.66,1-1.8,0-3.66.35-5.35-.72a2.33,2.33,0,0,0-1.56.07c-1.22.33-2.43.73-3.63,1.13a1.85,1.85,0,0,0-.86.47c-.28.35.41,3,.78,3.36.79.72,1.59,1.43,2.36,2.18,2.78,2.68,3.25,6.16,3.36,9.75a22.41,22.41,0,0,0,2.87,10.44,1.74,1.74,0,0,1-1.64-1.54c-.86-3.41-2.14-6.72-2.29-10.31-.14-3.25-.56-4.16-1.89-5.52a24.93,24.93,0,0,1-.17,4.45,12.52,12.52,0,0,1-1.68,4.17c-1.53,2.36-4.41,2.28-6-.05-1.85-2.67-2.05-5.66-1.53-8.76.06-.35.16-.69.25-1.07a6.81,6.81,0,0,0-2.94,5.69c-.17,3.81-1.31,7.38-2.26,11A2.54,2.54,0,0,1,539.22,398.8Z" transform="translate(-535.68 -345.68)"/></svg>

        <div class="form-container">
            <h2>HIPL SUPPORT DESK</h2>
            <svg class="neon" viewBox="0 0 600 100">
                <path fill="none" stroke="#dc3545" stroke-width="5" d="M 0 50 Q 50 10, 100 50 T 200 50 T 300 50 Q 350 10, 400 50 T 500 50 T 600 50" />
                <animate attributeName="stroke-dasharray" from="0, 600" to="600, 0" dur="1s" repeatCount="indefinite" />
                <animate attributeName="stroke-dashoffset" from="0" to="600" dur="1s" repeatCount="indefinite" />
            </svg>
            <form id="requestForm" name="requestForm">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" class="form-control" id="name" name="name" required>
                </div>

                <div class="form-group">
                    <label for="phone">Phone Number:</label>
                    <input type="text" class="form-control" id="phone" name="phone" required>
                </div>

                <div class="form-group">
                    <label for="email">Email Address:</label>
                    <input type="email" class="form-control" id="email" name="email" required>
                </div>

                <div class="form-group">
                    <label for="plant">Plant:</label>
                    <select class="form-control" id="plant" name="plant" required>
                        <option value="" disabled selected>Select an option</option>
                        <option value="Hemraj Industries Pvt Ltd">Hemraj Industries Pvt Ltd</option>
                        <option value="RadhaShyam Industries Pvt Ltd">RadhaShyam Industries Pvt Ltd</option>
                        <option value="Hemraj Rice Mill">Hemraj Rice Mill</option>
                        <option value="Rice Field">Rice Field Agri Industries Ltd</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="department">Department:</label>
                    <select class="form-control" id="department" name="department" required>
                        <option value="" disabled selected>Select an option</option>
                        <option value="HR">HR</option>
                        <option value="Account & Sale">Account & Sale</option>
                        <option value="Purchase">Purchase</option>
                        <option value="Ref & Solvant">Ref & Solvant</option>
                        <option value="Power Plant">Power Plant</option>
                        <option value="Store">Store</option>
                        <option value="Others">Others</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="requestType">Request Type:</label>
                    <select class="form-control" id="requestType" name="requestType" required>
                        <option value="" disabled selected>Select an option</option>
                        <option value="Software">Software</option>
                        <option value="Hardware">Hardware</option>
                        <option value="Camera Problem">Camera Problem</option>
                        <option value="Telephone Problem">Telephone Problem</option>
                        <option value="Network Problem">Network Problem</option>
                        <option value="MIS /Web app Support">MIS /Web app Support</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="priority">Priority:</label>
                    <select class="form-control" id="priority" name="priority" required>
                        <option value="" disabled selected>Select an option</option>
                        <option value="High">High</option>
                        <option value="Medium">Medium</option>
                        <option value="Low">Low</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="requesttypeName">Work By Name:</label>
                    <select class="form-control" id="requesttypeName" name="requesttypeName" required>
                        <option value="" disabled selected>Select an option</option>
                        <option value="Binod">Binod</option>
                        <option value="Goutam">Goutam</option>
                        <option value="All Person">All Person</option>
                    </select>
                </div>

                <div class="form-group">
                    <label for="description">Problem Description:</label>
                    <textarea class="form-control" id="description" name="description" rows="4" required></textarea>
                </div>

                <input type="submit" class="btn btn-primary btn-block" value="Submit">
                <div class="progress">Submitting your request...</div>
            </form>
            <dialog id="submissionDialog">
                <p>Form submitted successfully!</p>
                <button id="closeDialogButton" class="btn btn-secondary">Close</button>
            </dialog>
        </div>
		 
    </div>
</div>
    <!-- Bootstrap JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <script>
        const dialog = document.getElementById('submissionDialog');
        const scriptURL = 'https://script.google.com/macros/s/AKfycbwPXBRq1sIyR-ch6rG8YfBLG9vpZE8FvKX89bkzCCZ0pVfRPTNHkR3QEVslA1FbV-IA4g/exec';
        const form = document.forms['requestForm'];

        form.addEventListener('submit', e => {
            e.preventDefault();
            document.querySelector('.progress').style.display = 'block';
            fetch(scriptURL, { method: 'POST', body: new FormData(form) })
                .then(response => {
                    alert('Success!');
                    form.reset();
                    dialog.showModal();
                    document.getElementById('requestForm').style.display = 'none';
                    document.querySelector('.progress').style.display = 'none';
                })
                .catch(error => {
                    console.error('Error!', error.message);
                    document.querySelector('.progress').style.display = 'none';
                });
        });

        document.getElementById('closeDialogButton').addEventListener('click', function() {
            dialog.close();
        });
    </script>
</body>
</html>
