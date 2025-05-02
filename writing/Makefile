# Makefile for building Quarto documents

.PHONY: help render clean rebuild

# Default target
help:
	@echo "Makefile options:"
	@echo "  render   - Render the Quarto project"
	@echo "  clean    - Remove generated files"
	@echo "  rebuild  - Clean and then render the project"
	@echo "  view     - Open in Preview app for viewing"
	@echo "  help     - Show this help message"

render:
	quarto render --to pdf

clean:
	@rm -f _manuscritp/index.pdf

view:
	open _manuscript/index.pdf
	

rebuild: clean render
