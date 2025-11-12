# Workflow for publishing AEDB podcast episodes

## Create transcripts/subtitles

```bash
# Install auto-subtitle
pip install git+https://github.com/m1guelpf/auto-subtitle.git

# Create subtitles
cd auto_subtitle
auto_subtitle --output_dir ../AskErin_DearBeth/Transcripts --srt_only True /Users/eweisbar/Documents/projects/AEDB/Episodes/AskErinDearBeth_Episode_6.mp4

# Auto-clean subtitles
sed -i '' -f publishing_workflow/replacements.sed transcripts/AskErinDearBeth_Episode_21.srt
```
