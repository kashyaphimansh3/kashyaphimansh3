# UI Component Library - Unified Business Regulatory Platform

## Button Components

### Primary Button
```html
<button class="btn-primary">Submit Application</button>
```
- **Background**: Primary Blue (#1E3A8A)
- **Text Color**: White
- **Padding**: 12px 24px
- **Border Radius**: 8px
- **Font Weight**: 500
- **Height**: 44px (minimum touch target)
- **States**: Default, Hover, Focus, Disabled, Loading

### Secondary Button
```html
<button class="btn-secondary">Save as Draft</button>
```
- **Background**: Transparent
- **Text Color**: Primary Blue (#1E3A8A)
- **Border**: 2px solid Primary Blue
- **Same dimensions as primary button**

### Ghost Button
```html
<button class="btn-ghost">Cancel</button>
```
- **Background**: Transparent
- **Text Color**: Gray 600 (#4B5563)
- **No border**
- **Hover**: Light gray background

## Form Components

### Input Field
```html
<div class="form-group">
  <label for="business-name">Business Name *</label>
  <input type="text" id="business-name" class="form-input" placeholder="Enter your business name">
  <span class="form-help">As registered with authorities</span>
</div>
```
- **Height**: 44px
- **Border**: 1px solid Gray 300 (#D1D5DB)
- **Border Radius**: 6px
- **Padding**: 12px 16px
- **Font Size**: 16px
- **Focus**: Blue border, box-shadow

### Select Dropdown
```html
<div class="form-group">
  <label for="state">State/UT *</label>
  <select id="state" class="form-select">
    <option>Select your state</option>
    <option>Delhi</option>
    <option>Maharashtra</option>
  </select>
</div>
```
- **Same styling as input field**
- **Dropdown icon**: Chevron down
- **Custom styling for consistency**

### File Upload
```html
<div class="file-upload">
  <div class="file-upload-zone">
    <svg>...</svg>
    <p>Drop files here or <button>browse</button></p>
    <span>PDF, JPG, PNG up to 10MB</span>
  </div>
</div>
```
- **Drag and drop interface**
- **File type restrictions**
- **Progress indicators**
- **Multiple file support**

## Navigation Components

### Main Navigation
```html
<nav class="main-nav">
  <div class="nav-brand">
    <img src="logo.svg" alt="Government Logo">
    <h1>Business Portal</h1>
  </div>
  <ul class="nav-menu">
    <li><a href="/dashboard">Dashboard</a></li>
    <li><a href="/applications">Applications</a></li>
    <li><a href="/documents">Documents</a></li>
  </ul>
  <div class="nav-user">
    <button class="notification-btn">🔔</button>
    <div class="user-menu">...</div>
  </div>
</nav>
```

### Breadcrumbs
```html
<nav aria-label="Breadcrumb" class="breadcrumb">
  <ol>
    <li><a href="/dashboard">Dashboard</a></li>
    <li><a href="/applications">Applications</a></li>
    <li aria-current="page">New Application</li>
  </ol>
</nav>
```

### Tab Navigation
```html
<div class="tab-container">
  <nav class="tab-nav">
    <button class="tab-btn active">Basic Details</button>
    <button class="tab-btn">Documents</button>
    <button class="tab-btn">Review</button>
  </nav>
  <div class="tab-content">...</div>
</div>
```

## Card Components

### Information Card
```html
<div class="card">
  <div class="card-header">
    <h3>Application Status</h3>
    <span class="status-badge status-pending">Pending</span>
  </div>
  <div class="card-body">
    <p>Your application is under review...</p>
    <div class="card-actions">
      <button class="btn-secondary">View Details</button>
    </div>
  </div>
</div>
```

### Metric Card
```html
<div class="metric-card">
  <div class="metric-icon">📊</div>
  <div class="metric-content">
    <h4>Total Applications</h4>
    <span class="metric-value">24</span>
    <span class="metric-change positive">+12%</span>
  </div>
</div>
```

### Progress Card
```html
<div class="progress-card">
  <h4>Application Progress</h4>
  <div class="progress-bar">
    <div class="progress-fill" style="width: 60%"></div>
  </div>
  <div class="progress-steps">
    <span class="step completed">Submit</span>
    <span class="step completed">Review</span>
    <span class="step active">Approval</span>
    <span class="step">Complete</span>
  </div>
</div>
```

## Status Components

### Status Badges
```html
<span class="status-badge status-approved">Approved</span>
<span class="status-badge status-pending">Under Review</span>
<span class="status-badge status-rejected">Rejected</span>
<span class="status-badge status-draft">Draft</span>
```

### Progress Indicators
```html
<div class="progress-indicator">
  <div class="progress-step completed">
    <div class="step-marker">✓</div>
    <span>Application Submitted</span>
  </div>
  <div class="progress-step active">
    <div class="step-marker">2</div>
    <span>Document Verification</span>
  </div>
  <div class="progress-step">
    <div class="step-marker">3</div>
    <span>Final Approval</span>
  </div>
</div>
```

## Alert Components

### Success Alert
```html
<div class="alert alert-success">
  <svg class="alert-icon">...</svg>
  <div class="alert-content">
    <h4>Application Submitted Successfully</h4>
    <p>Reference ID: APP123456789</p>
  </div>
  <button class="alert-close">×</button>
</div>
```

### Warning Alert
```html
<div class="alert alert-warning">
  <svg class="alert-icon">⚠️</svg>
  <div class="alert-content">
    <h4>Documents Required</h4>
    <p>Please upload the missing documents to proceed.</p>
  </div>
</div>
```

## Modal Components

### Standard Modal
```html
<div class="modal-overlay">
  <div class="modal">
    <div class="modal-header">
      <h3>Confirm Submission</h3>
      <button class="modal-close">×</button>
    </div>
    <div class="modal-body">
      <p>Are you sure you want to submit this application?</p>
    </div>
    <div class="modal-footer">
      <button class="btn-secondary">Cancel</button>
      <button class="btn-primary">Submit</button>
    </div>
  </div>
</div>
```

## Data Display Components

### Data Table
```html
<div class="table-container">
  <table class="data-table">
    <thead>
      <tr>
        <th>Application ID</th>
        <th>Type</th>
        <th>Status</th>
        <th>Date</th>
        <th>Actions</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>APP123456</td>
        <td>Trade License</td>
        <td><span class="status-badge status-pending">Pending</span></td>
        <td>2024-01-15</td>
        <td>
          <button class="btn-ghost btn-sm">View</button>
        </td>
      </tr>
    </tbody>
  </table>
</div>
```

### List View
```html
<div class="list-view">
  <div class="list-item">
    <div class="list-icon">📄</div>
    <div class="list-content">
      <h4>Trade License Application</h4>
      <p>Submitted on Jan 15, 2024</p>
    </div>
    <div class="list-status">
      <span class="status-badge status-pending">Pending</span>
    </div>
  </div>
</div>
```

## Accessibility Features

### Focus Management
- Visible focus indicators on all interactive elements
- Proper tab order throughout components
- Skip links for keyboard navigation

### Screen Reader Support
- Semantic HTML structure
- ARIA labels and descriptions
- Live regions for dynamic content

### Color Independence
- Information conveyed through multiple means (color + text + icons)
- High contrast ratios maintained
- Pattern-based status indicators

## Responsive Behavior

### Breakpoints
- **Mobile**: 320px - 767px
- **Tablet**: 768px - 1023px
- **Desktop**: 1024px+

### Component Adaptations
- Stack elements vertically on mobile
- Collapse navigation to hamburger menu
- Adjust spacing and sizing for touch targets
- Simplify complex components for smaller screens

## Implementation Guidelines

### Naming Convention
- BEM methodology: `.block__element--modifier`
- Consistent naming across all components
- Semantic class names over presentational

### Spacing System
- 4px base unit
- Consistent padding and margins
- Responsive spacing adjustments

### Animation Guidelines
- Subtle transitions (200-300ms)
- Respect user preferences (reduce motion)
- Meaningful animations that aid understanding