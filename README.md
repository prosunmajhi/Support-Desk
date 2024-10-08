<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Request Form</title>
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
        }
    </style>
</head>
<body>
    
    <div class="form-container">
        <h2>HIPL SUPPORT DESK</h2>
        <svg class="neon" viewBox="0 0 600 100">
            <path fill="none" stroke="#dc3545" stroke-width="5" d="
                M 0 50
                Q 50 10, 100 50
                T 200 50
                T 300 50
                Q 350 10, 400 50
                T 500 50
                T 600 50" />
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
                <label for="requesttypeName">Request Type Name:</label>
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
