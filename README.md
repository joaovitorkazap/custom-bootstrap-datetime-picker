# custom-bootstrap-datetime-picker
Bootstrap Datetime Picker adapted for Bootstrap 4

I didn't modified where it takes the icons, i thought it was easier to use fon't-awesome icons:

  $('.datetimepicker').datetimepicker
    icons: {
            time: "fa fa-clock-o",
            date: "fa fa-calendar",
            up: "fa fa-arrow-up",
            down: "fa fa-arrow-down"
          }
    format: 'DD/MM/YYYY hh:mm A'
    widgetPositioning:
      vertical: 'top'
      horizontal: 'left'
