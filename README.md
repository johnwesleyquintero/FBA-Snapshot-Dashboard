# FBA Snapshot Dashboard v2.0 - README

## Project Overview
A modern, interactive dashboard for analyzing Amazon FBA inventory reports. This tool processes FBA Snapshot CSV files and provides a clean, searchable interface with real-time statistics and filtering capabilities.

## Key Features
- **CSV Upload & Processing**: Upload FBA Snapshot reports for instant analysis
- **Real-time Statistics**: Shows total products, available inventory, pending removals, and average 30-day shipments
- **Advanced Filtering**: Filter by product condition and recommended actions
- **Search Functionality**: Search across SKU, ASIN, and product name fields
- **Visual Indicators**: Color-coded badges and highlighted rows for important items
- **Pagination**: Efficient handling of large datasets (50 items per page)
- **Export Capability**: Download cleaned data as CSV with date-stamped filename
- **Responsive Design**: Works on desktop and mobile devices

## Technical Stack
- **Frontend**: HTML5, CSS3 (with CSS Grid/Flexbox), Vanilla JavaScript
- **CSV Processing**: Papa Parse library
- **Styling**: Modern CSS with custom properties and responsive design
- **No Backend Required**: Fully client-side application

## How to Use
1. **Upload**: Select your FBA Snapshot CSV file
2. **Process**: Click "Process Snapshot" to analyze the data
3. **Explore**: Use search and filters to find specific products
4. **Export**: Download cleaned data when needed

## File Format Requirements
- Must be a CSV file exported from Amazon Seller Central
- Expected columns: `sku`, `asin`, `product-name`, `condition`, `available`, `pending-removal-quantity`, `inv-age-*`, `units-shipped-t30`, `recommended-action`

## Design Philosophy
- **User-Centric**: Prioritizes quick identification of inventory issues
- **Performance-Focused**: Optimized for large datasets (1000+ products)
- **Mobile-First**: Responsive design for on-the-go analysis
- **Visual Hierarchy**: Clear information architecture with status indicators

## Security & Privacy
- All processing happens client-side (no data leaves your browser)
- No external tracking or analytics
- Secure data handling with no server storage

## Browser Compatibility
- Modern browsers supporting ES6+ (Chrome, Firefox, Safari, Edge)
- Mobile browsers with modern JavaScript support

## Development Notes
- Single HTML file with embedded CSS/JS for easy deployment
- Object-oriented JavaScript for maintainability
- Semantic HTML for accessibility
- CSS custom properties for easy theming

## Future Enhancement Ideas
- Export to PDF functionality
- Inventory aging visualization
- Bulk action recommendations
- Integration with other Amazon reports

## Troubleshooting
- Ensure CSV files are properly formatted with required columns
- Large files may take a few seconds to process
- For best results, use the latest version of your browser

---
*Built with focus on FBA operations efficiency and data-driven decision making*
