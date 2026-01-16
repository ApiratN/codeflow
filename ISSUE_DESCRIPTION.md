# 🚀 Feature Request: Enhanced JSON Export Report

## Problem
The current JSON export is useful but could be more comprehensive for programmatic analysis and integration with other tools.

## Proposed Solution
Enhance the JSON export to include all available audit data:

### Additional Data to Include:
- ✅ Churn data (commit frequency) for each file
- ✅ Complete function metadata (isExported, isClassMethod, type, isTopLevel)
- ✅ Full caller information for each function
- ✅ Duplicate code detection results
- ✅ Layer violations
- ✅ Suggestions and recommendations
- ✅ Enhanced architecture issues with full details
- ✅ Complete function statistics section

### Benefits:
- Enable programmatic analysis of codebase health
- Easy CI/CD integration
- Support for custom reporting tools
- Rich dataset for code quality metrics

## Use Case
Users want to export the complete audit data in JSON format to:
- Build custom dashboards
- Integrate with CI/CD pipelines
- Perform automated code quality analysis
- Generate custom reports

## Implementation Notes
The enhancement would modify the `generateReport('json')` function in `index.html` to include all available data from the analysis, while maintaining backward compatibility with existing export formats.
