SUBDIRS = appicons

gsettings_SCHEMAS = org.media-explorer.gschema.xml
@GSETTINGS_RULES@

jsondir = $(pkgdatadir)/json
dist_json_DATA = \
	json/info-bar.json		\
	json/info-panel-full.json	\
	json/info-panel-simple.json	\
	json/media-controls.json	\
	json/slide-show.json		\
	json/welcome.json		\
	$(NULL)

if HAVE_LIRC
extradir = $(pkgdatadir)
dist_extra_DATA = mex-lircrc
endif


styledir = $(pkgdatadir)/style
dist_style_DATA = \
	style/folder-tile-up.png \
	style/folder-tile.png \
	style/thumb-app.png \
	style/thumb-call-avatar-small.png \
	style/thumb-call-avatar.png \
	style/thumb-call-pip-off.png \
	style/thumb-disc.png \
	style/thumb-image.png \
	style/thumb-music.png \
	style/thumb-tv.png \
	style/thumb-video.png

EXTRA_DIST = \
	media-explorer.gresource.xml \
	json/music-player.json \
	style/bg-gradient.png \
	style/call-window-border.png \
	style/controls-bg.png \
	style/controls-container.png \
	style/details-actions-separator.png \
	style/footer.png \
	style/frame-bg.png \
	style/harderror-bg.png \
	style/highlight-bg.png \
	style/highlight-bg-white.png \
	style/highlight.png \
	style/icon-back.png \
	style/icon-fullscreen-active.png \
	style/icon-fullscreen-highlight.png \
	style/icon-fullscreen.png \
	style/icon-info-dark.png \
	style/icon-info.png \
	style/icon-pause-highlight.png \
	style/icon-pause.png \
	style/icon-play-highlight.png \
	style/icon-play.png \
	style/icon-rotate-highlight.png \
	style/icon-rotate.png \
	style/icon-stop-highlight.png \
	style/icon-stop.png \
	style/pip-border.png \
	style/queue-spinner-highlight.png \
	style/queue-spinner.png \
	style/spinner.png \
	style/style.css \
	style/text-input-bg.png \
	style/thumb-no-content.png \
	style/timeline-bg.png \
	style/timeline-highlight.png \
	style/timeline-highlight-white.png \
	style/timeline-playhead.png \
	style/volume-0.png \
	style/volume-10.png \
	style/volume-1.png \
	style/volume-2.png \
	style/volume-3.png \
	style/volume-4.png \
	style/volume-5.png \
	style/volume-6.png \
	style/volume-7.png \
	style/volume-8.png \
	style/volume-9.png \
	$(NULL)



if ENABLE_IDLE_VIDEO
EXTRA_DIST +=style/background-loop.mkv
endif

icondir = $(pkgdatadir)/icons/mex
dist_icon_DATA = \
		 icons/index.theme

icon_22x22dir = $(icondir)/22x22
dist_icon_22x22_DATA = \
		 icons/icon-info-highlight.png

icon_26x26dir = $(icondir)/26x26
dist_icon_26x26_DATA = \
		 icons/icon-back.png \
		 icons/icon-back-highlight.png \
		 icons/call-audio.png \
		 icons/call-audio-highlight.png \
		 icons/call-end.png \
		 icons/call-end-highlight.png \
		 icons/call-mic-mute.png \
		 icons/call-mic-mute-highlight.png \
		 icons/call-mic-on.png \
		 icons/call-mic-on-highlight.png \
		 icons/call-video.png \
		 icons/call-video-highlight.png \
		 icons/call-video-off.png \
		 icons/call-video-off-highlight.png \
		 icons/contact.png \
		 icons/contact-highlight.png \
		 icons/contact-add.png \
		 icons/contact-add-highlight.png \
		 icons/icon-notifications.png \
		 icons/icon-power.png \
		 icons/icon-power-highlight.png \
		 icons/icon-settings.png \
		 icons/icon-settings-highlight.png \
		 icons/icon-checkbox-off.png \
		 icons/icon-checkbox-off-highlight.png \
		 icons/icon-checkbox-on.png \
		 icons/icon-checkbox-on-highlight.png \
		 icons/media-addtoqueue-mex-highlight.png \
		 icons/media-addtoqueue-mex.png \
		 icons/media-eject-mex-highlight.png \
		 icons/media-eject-mex.png \
		 icons/media-removefromqueue-mex-highlight.png \
		 icons/media-removefromqueue-mex.png \
		 icons/media-watch-from-beginning-mex-highlight.png \
		 icons/media-watch-from-beginning-mex.png \
		 icons/media-watch-mex-highlight.png \
		 icons/media-watch-mex.png \
		 icons/media-share-mex.png \
		 icons/media-share-mex-highlight.png \
		 icons/player-subtitles.png \
		 icons/player-subtitles-highlight.png \
		 icons/x-mex-app-launch-mex.png \
		 icons/x-mex-app-launch-mex-highlight.png \
		 icons/stock_left-mex-highlight.png \
		 icons/stock_left-mex.png \
		 icons/stock_right-mex-highlight.png \
		 icons/stock_right-mex.png \
		 icons/icon-panelheader-apps.png \
		 icons/icon-panelheader-apps-highlight.png \
		 icons/icon-panelheader-computer-highlight.png \
		 icons/icon-panelheader-computer.png \
		 icons/icon-panelheader-photos.png \
		 icons/icon-panelheader-photos-highlight.png \
		 icons/icon-panelheader-recommended.png \
		 icons/icon-panelheader-recommended-highlight.png \
		 icons/icon-panelheader-recorded.png \
		 icons/icon-panelheader-recorded-highlight.png \
		 icons/icon-panelheader-search.png \
		 icons/icon-panelheader-search-highlight.png \
		 icons/icon-panelheader-tv.png \
		 icons/icon-panelheader-tv-highlight.png \
		 icons/icon-panelheader-music.png \
		 icons/icon-panelheader-music-highlight.png \
		 icons/icon-panelheader-queue-highlight.png \
		 icons/icon-panelheader-queue.png \
		 icons/icon-panelheader-usb-highlight.png \
		 icons/icon-panelheader-usb.png \
		 icons/icon-panelheader-videos.png \
		 icons/icon-panelheader-videos-highlight.png \
		 icons/x-mex-playing.png \
		 icons/x-mex-playing-highlight.png

applicationsdir = $(datadir)/applications
dist_applications_DATA =			\
	media-explorer.desktop			\
	$(NULL)

griloconfdir = $(pkgdatadir)
dist_griloconf_DATA = grilo-system.conf
