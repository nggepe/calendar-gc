<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <link rel="stylesheet" href="./src/calendar-gc.css">
  <style>
    html,
    body {
      margin: 0;
      overflow-x: hidden;
    }
  </style>
</head>

<body>
  <div id="calendar" style="padding: 1rem;"></div>
</body>
<script src="https://code.jquery.com/jquery-3.6.0.min.js"
  integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
<script src="./dist/calendar-gc.min.js"></script>
<script>
  $(function (e) {
    var calendar = $("#calendar").calendarGC({
      dayBegin: 0,
      prevIcon: '&#x3c;',
      nextIcon: '&#x3e;',
      onPrevMonth: function (e) {
        console.log("prev");
        console.log(e);
      },
      onNextMonth: function (e) {
        console.log("next");
        console.log(e);
      },
      events: getHoliday(),
      onclickDate: function (e, data) {
        console.log(e, data);
      }
    });
  });

  function getHoliday() {
    var d = new Date();
    var totalDay = new Date(d.getFullYear(), d.getMonth(), 0).getDate();
    var events = [];

    for (var i = 1; i <= totalDay; i++) {
      var newDate = new Date(d.getFullYear(), d.getMonth(), i);
      if (newDate.getDay() == 0) {   //if Sunday
        events.push({
          date: newDate,
          eventName: "Sunday free",
          className: "badge bg-danger",
          onclick(e, data) {
            console.log(data);
          },
          dateColor: "red"
        });
      }
      if (newDate.getDay() == 6) {   //if Saturday
        events.push({
          date: newDate,
          eventName: "Saturday free",
          className: "badge bg-danger",
          onclick(e, data) {
            console.log(data);
          },
          dateColor: "red"
        });
      }

    }
    return events;
  }

  getHoliday()
</script>

</html>