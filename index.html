<!DOCTYPE html>
<html lang="ku">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سیستەمی مدیریتی حەوالە و قەرز</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #4e73df;
            --secondary-color: #1cc88a;
            --danger-color: #e74a3b;
            --warning-color: #f6c23e;
            --info-color: #36b9cc;
            --dark-color: #5a5c69;
            --light-color: #f8f9fc;
        }
        
        body {
            background-color: #f8f9fc;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        .sidebar {
            position: fixed;
            top: 0;
            left: 0;
            width: 250px;
            height: 100vh;
            background: linear-gradient(180deg, var(--primary-color) 10%, #224abe 100%);
            z-index: 100;
            transition: all 0.3s;
            box-shadow: 0 0.15rem 1.75rem 0 rgba(58, 59, 69, 0.15);
        }
        
        .sidebar-brand {
            height: 70px;
            padding: 1.5rem 1rem;
            font-size: 1.2rem;
            font-weight: 800;
            color: #fff;
            text-align: center;
            text-transform: uppercase;
            letter-spacing: 0.05rem;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .sidebar-nav {
            padding-top: 1rem;
        }
        
        .sidebar-item {
            position: relative;
            margin: 0 1rem;
        }
        
        .sidebar-link {
            padding: 0.75rem 1rem;
            color: rgba(255, 255, 255, 0.8);
            text-decoration: none;
            display: flex;
            align-items: center;
            border-radius: 0.35rem;
            transition: all 0.3s;
        }
        
        .sidebar-link:hover {
            color: #fff;
            background-color: rgba(255, 255, 255, 0.1);
        }
        
        .sidebar-link i {
            margin-right: 0.5rem;
        }
        
        .content {
            margin-left: 250px;
            padding: 1.5rem;
        }
        
        .card {
            border: none;
            border-radius: 0.35rem;
            box-shadow: 0 0.15rem 1.75rem 0 rgba(58, 59, 69, 0.1);
            margin-bottom: 1.5rem;
        }
        
        .card-header {
            background-color: #f8f9fc;
            border-bottom: 1px solid #e3e6f0;
            padding: 0.75rem 1.25rem;
            font-weight: 700;
        }
        
        .dashboard-card {
            border-left: 4px solid;
        }
        
        .dashboard-card-income {
            border-left-color: var(--secondary-color);
        }
        
        .dashboard-card-expense {
            border-left-color: var(--primary-color);
        }
        
        .dashboard-card-debt {
            border-left-color: var(--danger-color);
        }
        
        .dashboard-card-deposit {
            border-left-color: var(--warning-color);
        }
        
        .section {
            display: none;
        }
        
        .active-section {
            display: block;
        }
        
        .search-suggestions {
            position: absolute;
            background: white;
            width: 100%;
            max-height: 200px;
            overflow-y: auto;
            z-index: 1000;
            border: 1px solid #ddd;
            border-radius: 0 0 4px 4px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        
        .suggestion-item {
            padding: 8px 12px;
            cursor: pointer;
            border-bottom: 1px solid #eee;
        }
        
        .suggestion-item:hover {
            background-color: #f5f5f5;
        }
        
        .table-responsive {
            overflow-x: auto;
        }
        
        .btn-primary {
            background-color: var(--primary-color);
            border-color: var(--primary-color);
        }
        
        .btn-success {
            background-color: var(--secondary-color);
            border-color: var(--secondary-color);
        }
        
        .btn-danger {
            background-color: var(--danger-color);
            border-color: var(--danger-color);
        }
        
        .btn-warning {
            background-color: var(--warning-color);
            border-color: var(--warning-color);
        }
        
        .text-primary {
            color: var(--primary-color) !important;
        }
        
        .text-success {
            color: var(--secondary-color) !important;
        }
        
        .text-danger {
            color: var(--danger-color) !important;
        }
        
        .text-warning {
            color: var(--warning-color) !important;
        }
        
        .bg-primary {
            background-color: var(--primary-color) !important;
        }
        
        .bg-success {
            background-color: var(--secondary-color) !important;
        }
        
        .bg-danger {
            background-color: var(--danger-color) !important;
        }
        
        .bg-warning {
            background-color: var(--warning-color) !important;
        }
        
        .form-control:focus {
            border-color: var(--primary-color);
            box-shadow: 0 0 0 0.2rem rgba(78, 115, 223, 0.25);
        }
        
        @media (max-width: 768px) {
            .sidebar {
                width: 80px;
            }
            
            .sidebar-brand span {
                display: none;
            }
            
            .sidebar-link span {
                display: none;
            }
            
            .content {
                margin-left: 80px;
            }
        }
    </style>
</head>
<body>
    <!-- ناوەڕۆکی سیستەمەکە -->
    <div class="sidebar">
        <div class="sidebar-brand">
            <i class="fas fa-exchange-alt"></i> <span>سیستەمی حەوالە</span>
        </div>
        
        <ul class="sidebar-nav">
            <li class="sidebar-item">
                <a href="#" class="sidebar-link" data-section="dashboard">
                    <i class="fas fa-tachometer-alt"></i> <span>داشبۆرد</span>
                </a>
            </li>
            <li class="sidebar-item">
                <a href="#" class="sidebar-link" data-section="transfer">
                    <i class="fas fa-paper-plane"></i> <span>حەوالەکردن</span>
                </a>
            </li>
            <li class="sidebar-item">
                <a href="#" class="sidebar-link" data-section="received">
                    <i class="fas fa-hand-holding-usd"></i> <span>حەوالەکراو</span>
                </a>
            </li>
            <li class="sidebar-item">
                <a href="#" class="sidebar-link" data-section="schools">
                    <i class="fas fa-school"></i> <span>مەکتەبەکان</span>
                </a>
            </li>
            <li class="sidebar-item">
                <a href="#" class="sidebar-link" data-section="persons">
                    <i class="fas fa-users"></i> <span>کەسەکان</span>
                </a>
            </li>
            <li class="sidebar-item">
                <a href="#" class="sidebar-link" data-section="deposit">
                    <i class="fas fa-money-check"></i> <span>پارەی واسل</span>
                </a>
            </li>
            <li class="sidebar-item">
                <a href="#" class="sidebar-link" data-section="settings">
                    <i class="fas fa-cog"></i> <span>رێکخستن</span>
                </a>
            </li>
        </ul>
    </div>
    
    <div class="content">
        <!-- داشبۆرد -->
        <div id="dashboard" class="section active-section">
            <h2 class="mb-4">داشبۆرد</h2>
            
            <div class="row">
                <div class="col-xl-3 col-md-6 mb-4">
                    <div class="card dashboard-card dashboard-card-expense h-100">
                        <div class="card-body">
                            <div class="row align-items-center">
                                <div class="col mr-2">
                                    <div class="text-xs font-weight-bold text-primary text-uppercase mb-1">کۆی پارەی حەوالەکراو</div>
                                    <div class="h5 mb-0 font-weight-bold text-gray-800">٠ دینار</div>
                                </div>
                                <div class="col-auto">
                                    <i class="fas fa-paper-plane fa-2x text-gray-300"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="col-xl-3 col-md-6 mb-4">
                    <div class="card dashboard-card dashboard-card-income h-100">
                        <div class="card-body">
                            <div class="row align-items-center">
                                <div class="col mr-2">
                                    <div class="text-xs font-weight-bold text-success text-uppercase mb-1">کۆی پارەی وەرگیراو</div>
                                    <div class="h5 mb-0 font-weight-bold text-gray-800">٠ دینار</div>
                                </div>
                                <div class="col-auto">
                                    <i class="fas fa-hand-holding-usd fa-2x text-gray-300"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="col-xl-3 col-md-6 mb-4">
                    <div class="card dashboard-card dashboard-card-debt h-100">
                        <div class="card-body">
                            <div class="row align-items-center">
                                <div class="col mr-2">
                                    <div class="text-xs font-weight-bold text-danger text-uppercase mb-1">کۆی قەرزی کەسەکان</div>
                                    <div class="h5 mb-0 font-weight-bold text-gray-800">٠ دینار</div>
                                </div>
                                <div class="col-auto">
                                    <i class="fas fa-file-invoice-dollar fa-2x text-gray-300"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="col-xl-3 col-md-6 mb-4">
                    <div class="card dashboard-card dashboard-card-deposit h-100">
                        <div class="card-body">
                            <div class="row align-items-center">
                                <div class="col mr-2">
                                    <div class="text-xs font-weight-bold text-warning text-uppercase mb-1">کۆی پارەی واسلی کەسەکان</div>
                                    <div class="h5 mb-0 font-weight-bold text-gray-800">٠ دینار</div>
                                </div>
                                <div class="col-auto">
                                    <i class="fas fa-money-check fa-2x text-gray-300"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="row">
                <div class="col-12">
                    <div class="card">
                        <div class="card-header">مێژووی حەوالەکان</div>
                        <div class="card-body">
                            <div class="table-responsive">
                                <table class="table table-bordered" id="transferHistoryTable" width="100%" cellspacing="0">
                                    <thead>
                                        <tr>
                                            <th>ناوی کەس</th>
                                            <th>ناوی مەکتەب</th>
                                            <th>بڕی پارە</th>
                                            <th>کات</th>
                                            <th>جۆر</th>
                                        </tr>
                                    </thead>
                                    <tbody>
                                        <tr>
                                            <td colspan="5" class="text-center">هیچ حەوالەیەک تۆمارنەکراوە</td>
                                        </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- حەوالەکردن -->
        <div id="transfer" class="section">
            <h2 class="mb-4">حەوالەکردن</h2>
            
            <div class="card mb-4">
                <div class="card-header">گەڕان بەدوای کەس یان مەکتەب</div>
                <div class="card-body">
                    <div class="row">
                        <div class="col-md-6">
                            <div class="form-group">
                                <label for="personSearch">گەڕان بەدوای ناوی کەسەکان</label>
                                <div class="position-relative">
                                    <input type="text" class="form-control" id="personSearch" placeholder="ناوی کەس بنووسە">
                                    <div class="search-suggestions" id="personSuggestions" style="display: none;"></div>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="form-group">
                                <label for="schoolSearch">گەڕان بەدوای ناوی مەکتەبە</label>
                                <div class="position-relative">
                                    <input type="text" class="form-control" id="schoolSearch" placeholder="ناوی مەکتەبە بنووسە">
                                    <div class="search-suggestions" id="schoolSuggestions" style="display: none;"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="card mb-4">
                <div class="card-header">زانیاری حەوالە</div>
                <div class="card-body">
                    <form id="transferForm">
                        <div class="row">
                            <div class="col-md-6">
                                <div class="form-group">
                                    <label for="selectedPerson">کەس</label>
                                    <input type="text" class="form-control" id="selectedPerson" readonly>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="form-group">
                                    <label for="selectedSchool">مەکتەبە</label>
                                    <input type="text" class="form-control" id="selectedSchool" readonly>
                                </div>
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label for="transferAmount">بڕی پارە</label>
                            <input type="number" class="form-control" id="transferAmount" placeholder="بڕی پارە بنووسە">
                        </div>
                        
                        <div class="form-group">
                            <label for="transferDate">بەروار</label>
                            <input type="date" class="form-control" id="transferDate">
                        </div>
                        
                        <div class="form-group">
                            <label for="transferNotes">تێبینی</label>
                            <textarea class="form-control" id="transferNotes" rows="3"></textarea>
                        </div>
                        
                        <button type="submit" class="btn btn-primary">حەوالە بکە</button>
                        <button type="button" class="btn btn-secondary" id="printTransfer">چاپکردن</button>
                    </form>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">مێژووی حەوالەکان</div>
                <div class="card-body">
                    <div class="table-responsive">
                        <table class="table table-bordered" id="transferHistoryTable" width="100%" cellspacing="0">
                            <thead>
                                <tr>
                                    <th>ناوی کەس</th>
                                    <th>ناوی مەکتەب</th>
                                    <th>بڕی پارە</th>
                                    <th>بەروار</th>
                                    <th>کردارەکان</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td colspan="5" class="text-center">هیچ حەوالەیەک تۆمارنەکراوە</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- حەوالەکراو -->
        <div id="received" class="section">
            <h2 class="mb-4">حەوالەکراو</h2>
            
            <div class="card mb-4">
                <div class="card-header">گەڕان بەدوای مەکتەبە</div>
                <div class="card-body">
                    <div class="form-group">
                        <div class="position-relative">
                            <input type="text" class="form-control" id="receivedSchoolSearch" placeholder="ناوی مەکتەبە بنووسە">
                            <div class="search-suggestions" id="receivedSchoolSuggestions" style="display: none;"></div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">مێژووی پارەی وەرگیراو</div>
                <div class="card-body">
                    <div class="table-responsive">
                        <table class="table table-bordered" id="receivedHistoryTable" width="100%" cellspacing="0">
                            <thead>
                                <tr>
                                    <th>ناوی کەس</th>
                                    <th>ناوی مەکتەب</th>
                                    <th>بڕی پارە</th>
                                    <th>بەروار</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td colspan="4" class="text-center">هیچ حەوالەیەک تۆمارنەکراوە</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- مەکتەبەکان -->
        <div id="schools" class="section">
            <h2 class="mb-4">مەکتەبەکان</h2>
            
            <div class="card mb-4">
                <div class="card-header">گەڕان بەدوای مەکتەبە</div>
                <div class="card-body">
                    <div class="form-group">
                        <div class="position-relative">
                            <input type="text" class="form-control" id="schoolListSearch" placeholder="ناوی مەکتەبە بنووسە">
                            <div class="search-suggestions" id="schoolListSuggestions" style="display: none;"></div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="card mb-4">
                <div class="card-header">زیادکردنی مەکتەبی نوێ</div>
                <div class="card-body">
                    <form id="addSchoolForm">
                        <div class="form-group">
                            <label for="schoolName">ناوی مەکتەبە</label>
                            <input type="text" class="form-control" id="schoolName" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="schoolLocation">شوێنی مەکتەبە</label>
                            <input type="text" class="form-control" id="schoolLocation" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="schoolPhone">ژمارە موبایلی مەکتەبە</label>
                            <input type="tel" class="form-control" id="schoolPhone">
                        </div>
                        
                        <button type="submit" class="btn btn-primary">زیادکردن</button>
                    </form>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">لیستی مەکتەبەکان</div>
                <div class="card-body">
                    <div class="table-responsive">
                        <table class="table table-bordered" id="schoolsTable" width="100%" cellspacing="0">
                            <thead>
                                <tr>
                                    <th>ناوی مەکتەبە</th>
                                    <th>شوێن</th>
                                    <th>ژمارە موبایل</th>
                                    <th>کردارەکان</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td colspan="4" class="text-center">هیچ مەکتەبێک تۆمارنەکراوە</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- کەسەکان -->
        <div id="persons" class="section">
            <h2 class="mb-4">کەسەکان</h2>
            
            <div class="card mb-4">
                <div class="card-header">گەڕان بەدوای کەس</div>
                <div class="card-body">
                    <div class="form-group">
                        <div class="position-relative">
                            <input type="text" class="form-control" id="personListSearch" placeholder="ناوی کەس بنووسە">
                            <div class="search-suggestions" id="personListSuggestions" style="display: none;"></div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="card mb-4">
                <div class="card-header">زیادکردنی کەسی نوێ</div>
                <div class="card-body">
                    <form id="addPersonForm">
                        <div class="form-group">
                            <label for="personName">ناوی کەسەکە</label>
                            <input type="text" class="form-control" id="personName" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="partnerName">ناوی شەریکەکە (ئارەزوومەندانە)</label>
                            <input type="text" class="form-control" id="partnerName">
                        </div>
                        
                        <div class="form-group">
                            <label for="personPhone">ژمارە موبایلی کەسەکە</label>
                            <input type="tel" class="form-control" id="personPhone">
                        </div>
                        
                        <div class="form-group">
                            <label for="personLocation">شوێنی کەسەکە</label>
                            <input type="text" class="form-control" id="personLocation">
                        </div>
                        
                        <button type="submit" class="btn btn-primary">زیادکردن</button>
                    </form>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">لیستی کەسەکان</div>
                <div class="card-body">
                    <div class="table-responsive">
                        <table class="table table-bordered" id="personsTable" width="100%" cellspacing="0">
                            <thead>
                                <tr>
                                    <th>ناوی کەس</th>
                                    <th>ناوی شەریک</th>
                                    <th>ژمارە موبایل</th>
                                    <th>شوێن</th>
                                    <th>قەرز</th>
                                    <th>کردارەکان</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td colspan="6" class="text-center">هیچ کەسێک تۆمارنەکراوە</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- پارەی واسل -->
        <div id="deposit" class="section">
            <h2 class="mb-4">پارەی واسلکردنی کەسەکان</h2>
            
            <div class="card mb-4">
                <div class="card-header">گەڕان بەدوای کەس</div>
                <div class="card-body">
                    <div class="form-group">
                        <div class="position-relative">
                            <input type="text" class="form-control" id="depositPersonSearch" placeholder="ناوی کەس بنووسە">
                            <div class="search-suggestions" id="depositPersonSuggestions" style="display: none;"></div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="card mb-4">
                <div class="card-header">پارەی واسل</div>
                <div class="card-body">
                    <form id="depositForm">
                        <div class="form-group">
                            <label for="selectedDepositPerson">کەس</label>
                            <input type="text" class="form-control" id="selectedDepositPerson" readonly>
                        </div>
                        
                        <div class="form-group">
                            <label for="depositAmount">بڕی پارە</label>
                            <input type="number" class="form-control" id="depositAmount" placeholder="بڕی پارە بنووسە">
                        </div>
                        
                        <div class="form-group">
                            <label for="depositDate">بەروار</label>
                            <input type="date" class="form-control" id="depositDate">
                        </div>
                        
                        <div class="form-group">
                            <label for="depositNotes">تێبینی</label>
                            <textarea class="form-control" id="depositNotes" rows="3"></textarea>
                        </div>
                        
                        <button type="submit" class="btn btn-primary">پارە واسل بکە</button>
                    </form>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">مێژووی پارەی واسل</div>
                <div class="card-body">
                    <div class="table-responsive">
                        <table class="table table-bordered" id="depositHistoryTable" width="100%" cellspacing="0">
                            <thead>
                                <tr>
                                    <th>ناوی کەس</th>
                                    <th>بڕی پارە</th>
                                    <th>بەروار</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td colspan="3" class="text-center">هیچ پارەیەک واسل نەکراوە</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- رێکخستن -->
        <div id="settings" class="section">
            <h2 class="mb-4">رێکخستن</h2>
            
            <div class="card mb-4">
                <div class="card-header">باکەپ</div>
                <div class="card-body">
                    <div class="row">
                        <div class="col-md-6">
                            <div class="form-group">
                                <label>داتا هەلگرە</label>
                                <button class="btn btn-primary btn-block" id="backupBtn">باکەپی داتاکان وەرگرە</button>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="form-group">
                                <label>داتا هێنەرەوە</label>
                                <div class="custom-file">
                                    <input type="file" class="custom-file-input" id="restoreFile">
                                    <label class="custom-file-label" for="restoreFile">فایلێک هەڵبژێرە</label>
                                </div>
                                <button class="btn btn-success btn-block mt-2" id="restoreBtn">داتا هێنەرەوە</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="card">
                <div class="card-header">زانیاری سیستەم</div>
                <div class="card-body">
                    <p>ئەم سیستەمە بۆ بەڕێوەبردنی حەوالە و قەرز دروست کراوە.</p>
                    <p>هەموو داتاکان لە ناو وێبگەڕەکەتدا خەزن دەکرێن و دەتوانیت باکەپیان وەربگریت.</p>
                </div>
            </div>
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        $(document).ready(function() {
            // داتاکانی سیستەم
            let data = {
                persons: [],
                schools: [],
                transfers: [],
                deposits: []
            };
            
            // چێکردنەوەی داتا لە localStorage
            function loadData() {
                const savedData = localStorage.getItem('hawalaSystemData');
                if (savedData) {
                    data = JSON.parse(savedData);
                }
                updateAllTables();
                updateDashboard();
            }
            
            // پاشەکەوتکردنی داتا لە localStorage
            function saveData() {
                localStorage.setItem('hawalaSystemData', JSON.stringify(data));
                updateAllTables();
                updateDashboard();
            }
            
            // نوێکردنەوەی هەموو خشتەکان
            function updateAllTables() {
                updatePersonsTable();
                updateSchoolsTable();
                updateTransferHistoryTable();
                updateReceivedHistoryTable();
                updateDepositHistoryTable();
            }
            
            // نوێکردنەوەی داشبۆرد
            function updateDashboard() {
                // لێرەدا دەتوانیت ژمارەکان نوێ بکەیتەوە
                console.log("داشبۆرد نوێکرایەوە");
            }
            
            // گۆڕینی ناوەڕۆک بە کلیک کردن لەسەر لیستەی ناوەڕاست
            $('.sidebar-link').click(function(e) {
                e.preventDefault();
                const sectionId = $(this).data('section');
                $('.section').removeClass('active-section');
                $(`#${sectionId}`).addClass('active-section');
            });
            
            // زیادکردنی کەسی نوێ
            $('#addPersonForm').submit(function(e) {
                e.preventDefault();
                const person = {
                    id: Date.now(),
                    name: $('#personName').val(),
                    partner: $('#partnerName').val(),
                    phone: $('#personPhone').val(),
                    location: $('#personLocation').val(),
                    debt: 0
                };
                
                data.persons.push(person);
                saveData();
                this.reset();
                alert('کەسەکە بە سەرکەوتوویی زیادکرا');
            });
            
            // زیادکردنی مەکتەبی نوێ
            $('#addSchoolForm').submit(function(e) {
                e.preventDefault();
                const school = {
                    id: Date.now(),
                    name: $('#schoolName').val(),
                    location: $('#schoolLocation').val(),
                    phone: $('#schoolPhone').val()
                };
                
                data.schools.push(school);
                saveData();
                this.reset();
                alert('مەکتەبەکە بە سەرکەوتوویی زیادکرا');
            });
            
            // حەوالەکردن
            $('#transferForm').submit(function(e) {
                e.preventDefault();
                const transfer = {
                    id: Date.now(),
                    person: $('#selectedPerson').val(),
                    school: $('#selectedSchool').val(),
                    amount: parseInt($('#transferAmount').val()),
                    date: $('#transferDate').val(),
                    notes: $('#transferNotes').val(),
                    type: 'sent'
                };
                
                data.transfers.push(transfer);
                
                // زیادکردنی قەرز بۆ کەسەکە
                const personName = $('#selectedPerson').val();
                const person = data.persons.find(p => p.name === personName);
                if (person) {
                    person.debt += transfer.amount;
                }
                
                saveData();
                this.reset();
                alert('حەوالەکە بە سەرکەوتوویی ئەنجامدرا');
            });
            
            // پارەی واسل
            $('#depositForm').submit(function(e) {
                e.preventDefault();
                const deposit = {
                    id: Date.now(),
                    person: $('#selectedDepositPerson').val(),
                    amount: parseInt($('#depositAmount').val()),
                    date: $('#depositDate').val(),
                    notes: $('#depositNotes').val()
                };
                
                data.deposits.push(deposit);
                
                // کەمکردنەوەی قەرزی کەسەکە
                const personName = $('#selectedDepositPerson').val();
                const person = data.persons.find(p => p.name === personName);
                if (person) {
                    person.debt -= deposit.amount;
                    if (person.debt < 0) person.debt = 0;
                }
                
                saveData();
                this.reset();
                alert('پارەکە بە سەرکەوتوویی واسلکرا');
            });
            
            // نوێکردنەوەی خشتەی کەسەکان
            function updatePersonsTable() {
                const tbody = $('#personsTable tbody');
                tbody.empty();
                
                if (data.persons.length === 0) {
                    tbody.append('<tr><td colspan="6" class="text-center">هیچ کەسێک تۆمارنەکراوە</td></tr>');
                    return;
                }
                
                data.persons.forEach(person => {
                    const row = `
                        <tr>
                            <td>${person.name}</td>
                            <td>${person.partner || '-'}</td>
                            <td>${person.phone || '-'}</td>
                            <td>${person.location || '-'}</td>
                            <td>${person.debt} دینار</td>
                            <td>
                                <button class="btn btn-sm btn-info view-person" data-id="${person.id}">بینین</button>
                                <button class="btn btn-sm btn-danger delete-person" data-id="${person.id}">سڕینەوە</button>
                            </td>
                        </tr>
                    `;
                    tbody.append(row);
                });
            }
            
            // نوێکردنەوەی خشتەی مەکتەبەکان
            function updateSchoolsTable() {
                const tbody = $('#schoolsTable tbody');
                tbody.empty();
                
                if (data.schools.length === 0) {
                    tbody.append('<tr><td colspan="4" class="text-center">هیچ مەکتەبێک تۆمارنەکراوە</td></tr>');
                    return;
                }
                
                data.schools.forEach(school => {
                    const row = `
                        <tr>
                            <td>${school.name}</td>
                            <td>${school.location}</td>
                            <td>${school.phone || '-'}</td>
                            <td>
                                <button class="btn btn-sm btn-info view-school" data-id="${school.id}">بینین</button>
                                <button class="btn btn-sm btn-danger delete-school" data-id="${school.id}">سڕینەوە</button>
                            </td>
                        </tr>
                    `;
                    tbody.append(row);
                });
            }
            
            // نوێکردنەوەی خشتەی مێژووی حەوالەکان
            function updateTransferHistoryTable() {
                const tbody = $('#transferHistoryTable tbody');
                tbody.empty();
                
                const sentTransfers = data.transfers.filter(t => t.type === 'sent');
                
                if (sentTransfers.length === 0) {
                    tbody.append('<tr><td colspan="5" class="text-center">هیچ حەوالەیەک تۆمارنەکراوە</td></tr>');
                    return;
                }
                
                sentTransfers.forEach(transfer => {
                    const row = `
                        <tr>
                            <td>${transfer.person}</td>
                            <td>${transfer.school}</td>
                            <td>${transfer.amount} دینار</td>
                            <td>${transfer.date}</td>
                            <td>
                                <button class="btn btn-sm btn-info view-transfer" data-id="${transfer.id}">بینین</button>
                                <button class="btn btn-sm btn-danger delete-transfer" data-id="${transfer.id}">سڕینەوە</button>
                            </td>
                        </tr>
                    `;
                    tbody.append(row);
                });
            }
            
            // نوێکردنەوەی خشتەی مێژووی وەرگرتن
            function updateReceivedHistoryTable() {
                const tbody = $('#receivedHistoryTable tbody');
                tbody.empty();
                
                const receivedTransfers = data.transfers.filter(t => t.type === 'received');
                
                if (receivedTransfers.length === 0) {
                    tbody.append('<tr><td colspan="4" class="text-center">هیچ حەوالەیەک تۆمارنەکراوە</td></tr>');
                    return;
                }
                
                receivedTransfers.forEach(transfer => {
                    const row = `
                        <tr>
                            <td>${transfer.person}</td>
                            <td>${transfer.school}</td>
                            <td>${transfer.amount} دینار</td>
                            <td>${transfer.date}</td>
                        </tr>
                    `;
                    tbody.append(row);
                });
            }
            
            // نوێکردنەوەی خشتەی مێژووی پارەی واسل
            function updateDepositHistoryTable() {
                const tbody = $('#depositHistoryTable tbody');
                tbody.empty();
                
                if (data.deposits.length === 0) {
                    tbody.append('<tr><td colspan="3" class="text-center">هیچ پارەیەک واسل نەکراوە</td></tr>');
                    return;
                }
                
                data.deposits.forEach(deposit => {
                    const row = `
                        <tr>
                            <td>${deposit.person}</td>
                            <td>${deposit.amount} دینار</td>
                            <td>${deposit.date}</td>
                        </tr>
                    `;
                    tbody.append(row);
                });
            }
            
            // گەڕان بەدوای کەسەکان
            $('#personSearch, #personListSearch, #depositPersonSearch').on('input', function() {
                const searchTerm = $(this).val().toLowerCase();
                const suggestions = data.persons.filter(person => 
                    person.name.toLowerCase().includes(searchTerm)
                );
                
                const suggestionsId = $(this).attr('id') + 'Suggestions';
                const $suggestions = $('#' + suggestionsId);
                
                if (searchTerm.length === 0 || suggestions.length === 0) {
                    $suggestions.hide();
                    return;
                }
                
                $suggestions.empty();
                suggestions.forEach(person => {
                    $suggestions.append(`<div class="suggestion-item" data-name="${person.name}">${person.name}</div>`);
                });
                
                $suggestions.show();
            });
            
            // گەڕان بەدوای مەکتەبەکان
            $('#schoolSearch, #receivedSchoolSearch, #schoolListSearch').on('input', function() {
                const searchTerm = $(this).val().toLowerCase();
                const suggestions = data.schools.filter(school => 
                    school.name.toLowerCase().includes(searchTerm)
                );
                
                const suggestionsId = $(this).attr('id') + 'Suggestions';
                const $suggestions = $('#' + suggestionsId);
                
                if (searchTerm.length === 0 || suggestions.length === 0) {
                    $suggestions.hide();
                    return;
                }
                
                $suggestions.empty();
                suggestions.forEach(school => {
                    $suggestions.append(`<div class="suggestion-item" data-name="${school.name}">${school.name}</div>`);
                });
                
                $suggestions.show();
            });
            
            // هەڵبژاردنی پێشنیار
            $(document).on('click', '.suggestion-item', function() {
                const name = $(this).data('name');
                const inputId = $(this).parent().attr('id').replace('Suggestions', '');
                $('#' + inputId).val(name);
                $(this).parent().hide();
                
                // بۆ حەوالەکردن
                if (inputId === 'personSearch') {
                    $('#selectedPerson').val(name);
                } else if (inputId === 'schoolSearch') {
                    $('#selectedSchool').val(name);
                } else if (inputId === 'depositPersonSearch') {
                    $('#selectedDepositPerson').val(name);
                }
            });
            
            // باکەپ
            $('#backupBtn').click(function() {
                const dataStr = JSON.stringify(data);
                const dataUri = 'data:application/json;charset=utf-8,'+ encodeURIComponent(dataStr);
                
                const exportFileDefaultName = 'hawala-backup.json';
                
                const linkElement = document.createElement('a');
                linkElement.setAttribute('href', dataUri);
                linkElement.setAttribute('download', exportFileDefaultName);
                linkElement.click();
            });
            
            // هێنانەوەی داتا
            $('#restoreBtn').click(function() {
                const fileInput = $('#restoreFile')[0];
                if (fileInput.files.length === 0) {
                    alert('تکایە فایلێک هەڵبژێرە');
                    return;
                }
                
                const file = fileInput.files[0];
                const reader = new FileReader();
                
                reader.onload = function(e) {
                    try {
                        const restoredData = JSON.parse(e.target.result);
                        data = restoredData;
                        saveData();
                        alert('داتاکان بە سەرکەوتوویی هێنرانەوە');
                    } catch (error) {
                        alert('هەڵە لە خوێندنەوەی فایلەکە: ' + error.message);
                    }
                };
                
                reader.readAsText(file);
            });
            
            // دەستپێکردنی سیستەم
            loadData();
        });
    </script>
</body>
</html>
