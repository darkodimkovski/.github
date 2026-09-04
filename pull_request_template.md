# Power BI / Fabric Deployment Request

## General Information

### Type of Change
- [ ] Visual changes only
- [ ] Calculation changes
- [ ] Semantic model changes
- [ ] Data source changes
- [ ] Security (RLS) changes
- [ ] Refresh configuration changes

### First Production Deployment
- [ ] Yes
- [ ] No

### Business Justification

Describe the purpose of this deployment and expected business impact.

---

## Data Sources & Connectivity

List all data sources used by this solution.

| Data Source | Gateway Required (Y/N) | Authentication |
|-------------|------------------------|---------------|
|             |                        |               |

### Refresh Schedule

Example: Daily at 06:00 UTC

### Estimated Refresh Duration

Example: 25 minutes

---

## Security

### RLS Changes
- [ ] No RLS
- [ ] Existing RLS unchanged
- [ ] New/Updated RLS included

If RLS was changed, describe the roles.

### Production Access

List Azure AD groups or users requiring access after deployment.

---


## Deployment Checklist

### Connectivity
- [ ] All data sources documented
- [ ] Gateway access configured where required
- [ ] Service account access validated
- [ ] No personal credentials used
- [ ] No personal gateway used
- [ ] No local files referenced (Excel, CSV, Access, local drives)

### Data Model Validation
- [ ] Unused columns removed
- [ ] Unused tables removed
- [ ] Unnecessary calculated columns removed
- [ ] Unnecessary calculated tables avoided
- [ ] Data granularity reviewed
- [ ] Historical data volume reviewed

### Large Dataset Validation
- [ ] Not applicable
- [ ] Incremental Refresh implemented

### Report Performance
- [ ] Report performance tested
- [ ] No known performance issues
- [ ] Refresh completed successfully in DEV

### Testing
- [ ] Solution fully tested in DEV workspace
- [ ] Deployment impact reviewed
- [ ] Rollback approach understood

---

## Validation Evidence

Include screenshots, test results, or links to validation evidence.

---

## Owner Confirmation

By submitting this PR, I confirm:

- [ ] Solution has been tested before deployment
- [ ] Information provided is accurate
- [ ] Report and semantic model have been reasonably optimized
- [ ] Solution complies with Power BI Governance Policy
