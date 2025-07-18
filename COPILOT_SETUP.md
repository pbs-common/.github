# GitHub Copilot Organization Setup Guide

## Implementation Steps

### 1. Apply Custom Instructions
1. Navigate to: https://github.com/organizations/pbs-digital/settings/copilot/custom_instructions
2. Copy content from `copilot-instructions.md`
3. Paste into the custom instructions field

### 2. Stakeholder Review Process
1. Post in #us-eng Slack channel with:
   ```
   📋 GitHub Copilot Org Instructions Draft Ready
   
   Please review the proposed custom instructions for PBS GitHub Copilot:
   [Link to this file]
   
   Key changes:
   - Security questions → SECURITY.md reference
   - Minimal code standards
   - PBS enterprise alignment
   
   Feedback needed by [DATE]
   ```

### 3. Activation Checklist
- [ ] Stakeholder feedback collected
- [ ] Security team approval
- [ ] Instructions updated based on feedback
- [ ] Applied to organization settings
- [ ] Team notification sent

### 4. Validation
Test with common scenarios:
- Security-related code requests
- Standard development tasks
- Architecture questions

## Related References
- CAT-25176: Github default community health files
- [OpenAI Model Spec](https://github.com/openai/model_spec) - Specification framework
- PBS enterprise coding standards

## Model Spec Alignment
These instructions follow OpenAI Model Spec principles:
- **Clear Objective**: Consistent PBS enterprise assistance
- **Behavioral Guidelines**: Explicit do/don't lists
- **Capability Boundaries**: Security redirection to proper channels
- **Quality Standards**: Minimal, maintainable code