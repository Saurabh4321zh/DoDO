# DoDO
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarkari Results - Latest Government Jobs, Admit Cards, Results</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #0d6efd;
            --secondary-color: #6c757d;
            --dark-color: #343a40;
            --light-color: #f8f9fa;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f5f5f5;
        }
        
        .navbar-brand {
            font-weight: 700;
            color: var(--primary-color) !important;
            font-size: 1.8rem;
        }
        
        .nav-link {
            font-weight: 500;
        }
        
        .result-card {
            margin-bottom: 15px;
            border-left: 4px solid var(--primary-color);
            transition: transform 0.3s;
        }
        
        .result-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .result-date {
            color: var(--secondary-color);
            font-size: 0.9rem;
        }
        
        .result-title {
            color: var(--dark-color);
            font-weight: 600;
        }
        
        .result-org {
            color: var(--secondary-color);
            font-size: 0.95rem;
        }
        
        .badge-type {
            background-color: var(--primary-color);
        }
        
        .search-box {
            position: relative;
        }
        
        .search-box input {
            padding-right: 40px;
        }
        
        .search-box button {
            position: absolute;
            right: 10px;
            top: 50%;
            transform: translateY(-50%);
            background: none;
            border: none;
            color: var(--secondary-color);
        }
        
        .category-btn {
            border-radius: 20px;
            padding: 8px 15px;
            margin: 5px;
            font-weight: 500;
        }
        
        .footer {
            background-color: var(--dark-color);
            color: white;
            padding: 30px 0;
        }
        
        .footer a {
            color: var(--light-color);
            text-decoration: none;
        }
        
        .marquee {
            background-color: var(--primary-color);
            color: white;
            padding: 8px 0;
            font-weight: 500;
        }
    </style>
</head>
<body>
    <!-- Top Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-file-alt me-2"></i>SarkariResult
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fas fa-home me-1"></i> Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fas fa-bell me-1"></i> Notifications</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fas fa-question-circle me-1"></i> Help</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Marquee for important updates -->
    <div class="marquee">
        <div class="container">
            <marquee behavior="scroll" direction="left">
                <span class="me-4"><i class="fas fa-exclamation-circle me-2"></i>UPSC Civil Services Results 2023 declared - Check now!</span>
                <span class="me-4"><i class="fas fa-exclamation-circle me-2"></i>SSC CHSL Tier 1 Admit Card released</span>
                <span class="me-4"><i class="fas fa-exclamation-circle me-2"></i>IBPS PO Mains Results expected soon</span>
            </marquee>
        </div>
    </div>

    <!-- Main Content -->
    <div class="container my-4">
        <!-- Search Box -->
        <div class="row mb-4">
            <div class="col-md-8 mx-auto">
                <div class="search-box">
                    <input type="text" class="form-control form-control-lg" placeholder="Search for results, jobs, admit cards...">
                    <button type="submit"><i class="fas fa-search"></i></button>
                </div>
            </div>
        </div>

        <!-- Quick Categories -->
        <div class="row mb-4">
            <div class="col-12">
                <h5 class="mb-3">Quick Categories:</h5>
                <div class="d-flex flex-wrap">
                    <a href="#" class="btn btn-outline-primary category-btn"><i class="fas fa-bolt me-2"></i>Latest Results</a>
                    <a href="#" class="btn btn-outline-success category-btn"><i class="fas fa-user-graduate me-2"></i>Admission</a>
                    <a href="#" class="btn btn-outline-info category-btn"><i class="fas fa-key me-2"></i>Answer Key</a>
                    <a href="#" class="btn btn-outline-warning category-btn"><i class="fas fa-id-card me-2"></i>Admit Card</a>
                    <a href="#" class="btn btn-outline-danger category-btn"><i class="fas fa-briefcase me-2"></i>Jobs</a>
                    <a href="#" class="btn btn-outline-secondary category-btn"><i class="fas fa-book me-2"></i>Syllabus</a>
                </div>
            </div>
        </div>

        <!-- Latest Results -->
        <div class="row">
            <div class="col-md-8">
                <h4 class="mb-4"><i class="fas fa-bolt text-primary me-2"></i>Latest Results</h4>
                
                <!-- Result Cards -->
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-primary mb-2">Latest Result</span>
                        <h5 class="result-title">UPSC Civil Services Final Result 2023</h5>
                        <p class="result-org mb-2">Union Public Service Commission</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 12 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">View Result</a>
                        </div>
                    </div>
                </div>
                
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-success mb-2">Admission</span>
                        <h5 class="result-title">NEET UG 2023 Result</h5>
                        <p class="result-org mb-2">National Testing Agency (NTA)</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 10 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">View Result</a>
                        </div>
                    </div>
                </div>
                
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-warning mb-2">Admit Card</span>
                        <h5 class="result-title">SSC CHSL Tier 1 Admit Card 2023</h5>
                        <p class="result-org mb-2">Staff Selection Commission</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 8 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">Download</a>
                        </div>
                    </div>
                </div>
                
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-danger mb-2">Jobs</span>
                        <h5 class="result-title">IBPS PO XII Recruitment 2023</h5>
                        <p class="result-org mb-2">Institute of Banking Personnel Selection</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 5 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">Apply Now</a>
                        </div>
                    </div>
                </div>
                
                <div class="text-center mt-4">
                    <a href="#" class="btn btn-outline-primary">View All Results</a>
                </div>
            </div>
            
            <!-- Sidebar -->
            <div class="col-md-4">
                <div class="card mb-4">
                    <div class="card-header bg-primary text-white">
                        <h5 class="mb-0"><i class="fas fa-bell me-2"></i>Important Updates</h5>
                    </div>
                    <div class="list-group list-group-flush">
                        <a href="#" class="list-group-item list-group-item-action">SSC CGL 2023 Notification Released</a>
                        <a href="#" class="list-group-item list-group-item-action">UPSC CDS II 2023 Apply Online</a>
                        <a href="#" class="list-group-item list-group-item-action">IBPS RRB XII Registration Extended</a>
                        <a href="#" class="list-group-item list-group-item-action">Railway Group D Phase 4 Exam Date</a>
                        <a href="#" class="list-group-item list-group-item-action">UPPSC PCS 2023 Interview Schedule</a>
                    </div>
                </div>
                
                <div class="card mb-4">
                    <div class="card-header bg-success text-white">
                        <h5 class="mb-0"><i class="fas fa-university me-2"></i>Top Organizations</h5>
                    </div>
                    <div class="list-group list-group-flush">
                        <a href="#" class="list-group-item list-group-item-action">UPSC</a>
                        <a href="#" class="list-group-item list-group-item-action">SSC</a>
                        <a href="#" class="list-group-item list-group-item-action">IBPS</a>
                        <a href="#" class="list-group-item list-group-item-action">Railway Recruitment Board</a>
                        <a href="#" class="list-group-item list-group-item-action">State PSCs</a>
                    </div>
                </div>
                
                <div class="card">
                    <div class="card-header bg-info text-white">
                        <h5 class="mb-0"><i class="fas fa-calendar-alt me-2"></i>Upcoming Exams</h5>
                    </div>
                    <div class="list-group list-group-flush">
                        <a href="#" class="list-group-item list-group-item-action">SSC CHSL Tier 1 - 15 May 2023</a>
                        <a href="#" class="list-group-item list-group-item-action">IBPS PO XII Mains - 20 May 2023</a>
                        <a href="#" class="list-group-item list-group-item-action">UPSC CDS II - 25 May 2023</a>
                        <a href="#" class="list-group-item list-group-item-action">Railway Group D - 30 May 2023</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="footer mt-5">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h5>About SarkariResult</h5>
                    <p>The most trusted platform for all government job notifications, exam results, admit cards, and answer keys.</p>
                </div>
                <div class="col-md-4">
                    <h5>Quick Links</h5>
                    <ul class="list-unstyled">
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Home</a></li>
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Latest Jobs</a></li>
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Results</a></li>
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Admit Cards</a></li>
                    </ul>
                </div>
                <div class="col-md-4">
                    <h5>Contact Us</h5>
                    <ul class="list-unstyled">
                        <li><i class="fas fa-envelope me-2"></i> info@sarkariresult.com</li>
                        <li><i class="fas fa-phone me-2"></i> +91 1234567890</li>
                        <li><i class="fas fa-map-marker-alt me-2"></i> New Delhi, India</li>
                    </ul>
                </div>
            </div>
            <hr class="mt-4 bg-light">
            <div class="row">
       <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarkari Results - Latest Government Jobs, Admit Cards, Results</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #0d6efd;
            --secondary-color: #6c757d;
            --dark-color: #343a40;
            --light-color: #f8f9fa;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f5f5f5;
        }
        
        .navbar-brand {
            font-weight: 700;
            color: var(--primary-color) !important;
            font-size: 1.8rem;
        }
        
        .nav-link {
            font-weight: 500;
        }
        
        .result-card {
            margin-bottom: 15px;
            border-left: 4px solid var(--primary-color);
            transition: transform 0.3s;
        }
        
        .result-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .result-date {
            color: var(--secondary-color);
            font-size: 0.9rem;
        }
        
        .result-title {
            color: var(--dark-color);
            font-weight: 600;
        }
        
        .result-org {
            color: var(--secondary-color);
            font-size: 0.95rem;
        }
        
        .badge-type {
            background-color: var(--primary-color);
        }
        
        .search-box {
            position: relative;
        }
        
        .search-box input {
            padding-right: 40px;
        }
        
        .search-box button {
            position: absolute;
            right: 10px;
            top: 50%;
            transform: translateY(-50%);
            background: none;
            border: none;
            color: var(--secondary-color);
        }
        
        .category-btn {
            border-radius: 20px;
            padding: 8px 15px;
            margin: 5px;
            font-weight: 500;
        }
        
        .footer {
            background-color: var(--dark-color);
            color: white;
            padding: 30px 0;
        }
        
        .footer a {
            color: var(--light-color);
            text-decoration: none;
        }
        
        .marquee {
            background-color: var(--primary-color);
            color: white;
            padding: 8px 0;
            font-weight: 500;
        }
    </style>
</head>
<body>
    <!-- Top Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-file-alt me-2"></i>SarkariResult
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fas fa-home me-1"></i> Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fas fa-bell me-1"></i> Notifications</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fas fa-question-circle me-1"></i> Help</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Marquee for important updates -->
    <div class="marquee">
        <div class="container">
            <marquee behavior="scroll" direction="left">
                <span class="me-4"><i class="fas fa-exclamation-circle me-2"></i>UPSC Civil Services Results 2023 declared - Check now!</span>
                <span class="me-4"><i class="fas fa-exclamation-circle me-2"></i>SSC CHSL Tier 1 Admit Card released</span>
                <span class="me-4"><i class="fas fa-exclamation-circle me-2"></i>IBPS PO Mains Results expected soon</span>
            </marquee>
        </div>
    </div>

    <!-- Main Content -->
    <div class="container my-4">
        <!-- Search Box -->
        <div class="row mb-4">
            <div class="col-md-8 mx-auto">
                <div class="search-box">
                    <input type="text" class="form-control form-control-lg" placeholder="Search for results, jobs, admit cards...">
                    <button type="submit"><i class="fas fa-search"></i></button>
                </div>
            </div>
        </div>

        <!-- Quick Categories -->
        <div class="row mb-4">
            <div class="col-12">
                <h5 class="mb-3">Quick Categories:</h5>
                <div class="d-flex flex-wrap">
                    <a href="#" class="btn btn-outline-primary category-btn"><i class="fas fa-bolt me-2"></i>Latest Results</a>
                    <a href="#" class="btn btn-outline-success category-btn"><i class="fas fa-user-graduate me-2"></i>Admission</a>
                    <a href="#" class="btn btn-outline-info category-btn"><i class="fas fa-key me-2"></i>Answer Key</a>
                    <a href="#" class="btn btn-outline-warning category-btn"><i class="fas fa-id-card me-2"></i>Admit Card</a>
                    <a href="#" class="btn btn-outline-danger category-btn"><i class="fas fa-briefcase me-2"></i>Jobs</a>
                    <a href="#" class="btn btn-outline-secondary category-btn"><i class="fas fa-book me-2"></i>Syllabus</a>
                </div>
            </div>
        </div>

        <!-- Latest Results -->
        <div class="row">
            <div class="col-md-8">
                <h4 class="mb-4"><i class="fas fa-bolt text-primary me-2"></i>Latest Results</h4>
                
                <!-- Result Cards -->
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-primary mb-2">Latest Result</span>
                        <h5 class="result-title">UPSC Civil Services Final Result 2023</h5>
                        <p class="result-org mb-2">Union Public Service Commission</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 12 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">View Result</a>
                        </div>
                    </div>
                </div>
                
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-success mb-2">Admission</span>
                        <h5 class="result-title">NEET UG 2023 Result</h5>
                        <p class="result-org mb-2">National Testing Agency (NTA)</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 10 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">View Result</a>
                        </div>
                    </div>
                </div>
                
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-warning mb-2">Admit Card</span>
                        <h5 class="result-title">SSC CHSL Tier 1 Admit Card 2023</h5>
                        <p class="result-org mb-2">Staff Selection Commission</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 8 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">Download</a>
                        </div>
                    </div>
                </div>
                
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-danger mb-2">Jobs</span>
                        <h5 class="result-title">IBPS PO XII Recruitment 2023</h5>
                        <p class="result-org mb-2">Institute of Banking Personnel Selection</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 5 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">Apply Now</a>
                        </div>
                    </div>
                </div>
                
                <div class="text-center mt-4">
                    <a href="#" class="btn btn-outline-primary">View All Results</a>
                </div>
            </div>
            
            <!-- Sidebar -->
            <div class="col-md-4">
                <div class="card mb-4">
                    <div class="card-header bg-primary text-white">
                        <h5 class="mb-0"><i class="fas fa-bell me-2"></i>Important Updates</h5>
                    </div>
                    <div class="list-group list-group-flush">
                        <a href="#" class="list-group-item list-group-item-action">SSC CGL 2023 Notification Released</a>
                        <a href="#" class="list-group-item list-group-item-action">UPSC CDS II 2023 Apply Online</a>
                        <a href="#" class="list-group-item list-group-item-action">IBPS RRB XII Registration Extended</a>
                        <a href="#" class="list-group-item list-group-item-action">Railway Group D Phase 4 Exam Date</a>
                        <a href="#" class="list-group-item list-group-item-action">UPPSC PCS 2023 Interview Schedule</a>
                    </div>
                </div>
                
                <div class="card mb-4">
                    <div class="card-header bg-success text-white">
                        <h5 class="mb-0"><i class="fas fa-university me-2"></i>Top Organizations</h5>
                    </div>
                    <div class="list-group list-group-flush">
                        <a href="#" class="list-group-item list-group-item-action">UPSC</a>
                        <a href="#" class="list-group-item list-group-item-action">SSC</a>
                        <a href="#" class="list-group-item list-group-item-action">IBPS</a>
                        <a href="#" class="list-group-item list-group-item-action">Railway Recruitment Board</a>
                        <a href="#" class="list-group-item list-group-item-action">State PSCs</a>
                    </div>
                </div>
                
                <div class="card">
                    <div class="card-header bg-info text-white">
                        <h5 class="mb-0"><i class="fas fa-calendar-alt me-2"></i>Upcoming Exams</h5>
                    </div>
                    <div class="list-group list-group-flush">
                        <a href="#" class="list-group-item list-group-item-action">SSC CHSL Tier 1 - 15 May 2023</a>
                        <a href="#" class="list-group-item list-group-item-action">IBPS PO XII Mains - 20 May 2023</a>
                        <a href="#" class="list-group-item list-group-item-action">UPSC CDS II - 25 May 2023</a>
                        <a href="#" class="list-group-item list-group-item-action">Railway Group D - 30 May 2023</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="footer mt-5">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h5>About SarkariResult</h5>
                    <p>The most trusted platform for all government job notifications, exam results, admit cards, and answer keys.</p>
                </div>
                <div class="col-md-4">
                    <h5>Quick Links</h5>
                    <ul class="list-unstyled">
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Home</a></li>
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Latest Jobs</a></li>
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Results</a></li>
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Admit Cards</a></li>
                    </ul>
                </div>
                <div class="col-md-4">
                    <h5>Contact Us</h5>
                    <ul class="list-unstyled">
                        <li><i class="fas fa-envelope me-2"></i> info@sarkariresult.com</li>
                        <li><i class="fas fa-phone me-2"></i> +91 1234567890</li>
                        <li><i class="fas fa-map-marker-alt me-2"></i> New Delhi, India</li>
                    </ul>
                </div>
            </div>
            <hr class="mt-4 bg-light">
            <div class="row">
                <div class="col-md-6">
                    <p class="mb-0">&copy; 2023 SarkariResult. All rights reserved.</p>
                </div>
                <div class="col-md-6 text-md-end">
                    <a href="#" class="text-white me-3"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" class="text-white me-3"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="text-white me-3"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="text-white"><i class="fab fa-linkedin-in"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarkari Results - Latest Government Jobs, Admit Cards, Results</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #0d6efd;
            --secondary-color: #6c757d;
            --dark-color: #343a40;
            --light-color: #f8f9fa;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f5f5f5;
        }
        
        .navbar-brand {
            font-weight: 700;
            color: var(--primary-color) !important;
            font-size: 1.8rem;
        }
        
        .nav-link {
            font-weight: 500;
        }
        
        .result-card {
            margin-bottom: 15px;
            border-left: 4px solid var(--primary-color);
            transition: transform 0.3s;
        }
        
        .result-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .result-date {
            color: var(--secondary-color);
            font-size: 0.9rem;
        }
        
        .result-title {
            color: var(--dark-color);
            font-weight: 600;
        }
        
        .result-org {
            color: var(--secondary-color);
            font-size: 0.95rem;
        }
        
        .badge-type {
            background-color: var(--primary-color);
        }
        
        .search-box {
            position: relative;
        }
        
        .search-box input {
            padding-right: 40px;
        }
        
        .search-box button {
            position: absolute;
            right: 10px;
            top: 50%;
            transform: translateY(-50%);
            background: none;
            border: none;
            color: var(--secondary-color);
        }
        
        .category-btn {
            border-radius: 20px;
            padding: 8px 15px;
            margin: 5px;
            font-weight: 500;
        }
        
        .footer {
            background-color: var(--dark-color);
            color: white;
            padding: 30px 0;
        }
        
        .footer a {
            color: var(--light-color);
            text-decoration: none;
        }
        
        .marquee {
            background-color: var(--primary-color);
            color: white;
            padding: 8px 0;
            font-weight: 500;
        }
    </style>
</head>
<body>
    <!-- Top Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-file-alt me-2"></i>SarkariResult
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fas fa-home me-1"></i> Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fas fa-bell me-1"></i> Notifications</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fas fa-question-circle me-1"></i> Help</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Marquee for important updates -->
    <div class="marquee">
        <div class="container">
            <marquee behavior="scroll" direction="left">
                <span class="me-4"><i class="fas fa-exclamation-circle me-2"></i>UPSC Civil Services Results 2023 declared - Check now!</span>
                <span class="me-4"><i class="fas fa-exclamation-circle me-2"></i>SSC CHSL Tier 1 Admit Card released</span>
                <span class="me-4"><i class="fas fa-exclamation-circle me-2"></i>IBPS PO Mains Results expected soon</span>
            </marquee>
        </div>
    </div>

    <!-- Main Content -->
    <div class="container my-4">
        <!-- Search Box -->
        <div class="row mb-4">
            <div class="col-md-8 mx-auto">
                <div class="search-box">
                    <input type="text" class="form-control form-control-lg" placeholder="Search for results, jobs, admit cards...">
                    <button type="submit"><i class="fas fa-search"></i></button>
                </div>
            </div>
        </div>

        <!-- Quick Categories -->
        <div class="row mb-4">
            <div class="col-12">
                <h5 class="mb-3">Quick Categories:</h5>
                <div class="d-flex flex-wrap">
                    <a href="#" class="btn btn-outline-primary category-btn"><i class="fas fa-bolt me-2"></i>Latest Results</a>
                    <a href="#" class="btn btn-outline-success category-btn"><i class="fas fa-user-graduate me-2"></i>Admission</a>
                    <a href="#" class="btn btn-outline-info category-btn"><i class="fas fa-key me-2"></i>Answer Key</a>
                    <a href="#" class="btn btn-outline-warning category-btn"><i class="fas fa-id-card me-2"></i>Admit Card</a>
                    <a href="#" class="btn btn-outline-danger category-btn"><i class="fas fa-briefcase me-2"></i>Jobs</a>
                    <a href="#" class="btn btn-outline-secondary category-btn"><i class="fas fa-book me-2"></i>Syllabus</a>
                </div>
            </div>
        </div>

        <!-- Latest Results -->
        <div class="row">
            <div class="col-md-8">
                <h4 class="mb-4"><i class="fas fa-bolt text-primary me-2"></i>Latest Results</h4>
                
                <!-- Result Cards -->
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-primary mb-2">Latest Result</span>
                        <h5 class="result-title">UPSC Civil Services Final Result 2023</h5>
                        <p class="result-org mb-2">Union Public Service Commission</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 12 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">View Result</a>
                        </div>
                    </div>
                </div>
                
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-success mb-2">Admission</span>
                        <h5 class="result-title">NEET UG 2023 Result</h5>
                        <p class="result-org mb-2">National Testing Agency (NTA)</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 10 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">View Result</a>
                        </div>
                    </div>
                </div>
                
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-warning mb-2">Admit Card</span>
                        <h5 class="result-title">SSC CHSL Tier 1 Admit Card 2023</h5>
                        <p class="result-org mb-2">Staff Selection Commission</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 8 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">Download</a>
                        </div>
                    </div>
                </div>
                
                <div class="card result-card">
                    <div class="card-body">
                        <span class="badge badge-type bg-danger mb-2">Jobs</span>
                        <h5 class="result-title">IBPS PO XII Recruitment 2023</h5>
                        <p class="result-org mb-2">Institute of Banking Personnel Selection</p>
                        <div class="d-flex justify-content-between align-items-center">
                            <span class="result-date"><i class="far fa-calendar-alt me-1"></i>Published on: 5 May 2023</span>
                            <a href="#" class="btn btn-sm btn-primary">Apply Now</a>
                        </div>
                    </div>
                </div>
                
                <div class="text-center mt-4">
                    <a href="#" class="btn btn-outline-primary">View All Results</a>
                </div>
            </div>
            
            <!-- Sidebar -->
            <div class="col-md-4">
                <div class="card mb-4">
                    <div class="card-header bg-primary text-white">
                        <h5 class="mb-0"><i class="fas fa-bell me-2"></i>Important Updates</h5>
                    </div>
                    <div class="list-group list-group-flush">
                        <a href="#" class="list-group-item list-group-item-action">SSC CGL 2023 Notification Released</a>
                        <a href="#" class="list-group-item list-group-item-action">UPSC CDS II 2023 Apply Online</a>
                        <a href="#" class="list-group-item list-group-item-action">IBPS RRB XII Registration Extended</a>
                        <a href="#" class="list-group-item list-group-item-action">Railway Group D Phase 4 Exam Date</a>
                        <a href="#" class="list-group-item list-group-item-action">UPPSC PCS 2023 Interview Schedule</a>
                    </div>
                </div>
                
                <div class="card mb-4">
                    <div class="card-header bg-success text-white">
                        <h5 class="mb-0"><i class="fas fa-university me-2"></i>Top Organizations</h5>
                    </div>
                    <div class="list-group list-group-flush">
                        <a href="#" class="list-group-item list-group-item-action">UPSC</a>
                        <a href="#" class="list-group-item list-group-item-action">SSC</a>
                        <a href="#" class="list-group-item list-group-item-action">IBPS</a>
                        <a href="#" class="list-group-item list-group-item-action">Railway Recruitment Board</a>
                        <a href="#" class="list-group-item list-group-item-action">State PSCs</a>
                    </div>
                </div>
                
                <div class="card">
                    <div class="card-header bg-info text-white">
                        <h5 class="mb-0"><i class="fas fa-calendar-alt me-2"></i>Upcoming Exams</h5>
                    </div>
                    <div class="list-group list-group-flush">
                        <a href="#" class="list-group-item list-group-item-action">SSC CHSL Tier 1 - 15 May 2023</a>
                        <a href="#" class="list-group-item list-group-item-action">IBPS PO XII Mains - 20 May 2023</a>
                        <a href="#" class="list-group-item list-group-item-action">UPSC CDS II - 25 May 2023</a>
                        <a href="#" class="list-group-item list-group-item-action">Railway Group D - 30 May 2023</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="footer mt-5">
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h5>About SarkariResult</h5>
                    <p>The most trusted platform for all government job notifications, exam results, admit cards, and answer keys.</p>
                </div>
                <div class="col-md-4">
                    <h5>Quick Links</h5>
                    <ul class="list-unstyled">
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Home</a></li>
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Latest Jobs</a></li>
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Results</a></li>
                        <li><a href="#"><i class="fas fa-angle-right me-2"></i>Admit Cards</a></li>
                    </ul>
                </div>
                <div class="col-md-4">
                    <h5>Contact Us</h5>
                    <ul class="list-unstyled">
                        <li><i class="fas fa-envelope me-2"></i> info@sarkariresult.com</li>
                        <li><i class="fas fa-phone me-2"></i> +91 1234567890</li>
                        <li><i class="fas fa-map-marker-alt me-2"></i> New Delhi, India</li>
                    </ul>
                </div>
            </div>
            <hr class="mt-4 bg-light">
            <div class="row">
                <div class="col-md-6">
                    <p class="mb-0">&copy; 2023 SarkariResult. All rights reserved.</p>
                </div>
                <div class="col-md-6 text-md-end">
                    <a href="#" class="text-white me-3"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" class="text-white me-3"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="text-white me-3"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="text-white"><i class="fab fa-linkedin-in"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
