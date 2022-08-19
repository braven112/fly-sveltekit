<div class="container upcomingTrips">
  <auro-header level="3" margin="top" size="none" display="500">Upcoming Trips</auro-header>
  <table class="auro_table upcomingTripData">
    <tr>
      <th class="upcomingTripFlight">Trip</th>
      <th class="upcomingTripDetails">Details</th>
      <th class="upcomingTripConfirmation">Confirmation</th>
      <th class="upcomingTripCancel" />
    </tr>
    <tr>
      <td class="upcomingTripFlight">
        <auro-header level="6" margin="top" size="none" display="300">
          <auro-datetime type="date" month="short" weekday="short" />
        </auro-header>
        <auro-flight flights='["AS 333"]' duration="2h 05m" departureTime="6:50 am" departureStation="PSP" arrivalTime="8:55 am" arrivalStation="SEA">
          <auro-flightline />
        </auro-flight>
      </td>
      <td class="upcomingTripFlightDetails">
        <div class="upcomingTripDetails">
          <div class="upcomingTripTravelers">2 travelers</div>

          <div class="upcomingTripPriority">
            <auro-button onClick="toggleInterruption('#priority')" secondary>Priority: E1Y.14</auro-button>
          </div>

          <div class="upcomingTripType fineprint">Pleasure Space Available (Coach)</div>
        </div>
      </td>
      <td class="upcomingTripConfirmation">qwerty</td>
      <td class="upcomingTripCancel">
        <auro-button tertiary>Cancel</auro-button>
      </td>
    </tr>
    <tr>
      <td class="upcomingTripFlight">
        <auro-header level="6" margin="top" size="none" display="300">Mon, July 4, 2022</auro-header>
        <auro-flight flights='["AS 880"]' duration="5h 45m" daysChanged="1" departureTime="10:50 pm" departureStation="KOA" arrivalTime="6:35 am" ArrivalStation="SEA">
          <auro-flightline />
        </auro-flight>
      </td>
      <td class="upcomingTripFlightDetails">
        <div class="upcomingTripDetails">
          <div class="upcomingTripTravelers">1 travelers</div>

          <div class="upcomingTripPriority">
            <auro-button onClick="toggleInterruption('#priority')" secondary>Priority: E1Y.14</auro-button>
          </div>

          <div class="upcomingTripType fineprint">Pleasure Space Available (Coach)</div>
        </div>
      </td>
      <td class="upcomingTripConfirmation">asdfas</td>
      <td class="upcomingTripCancel">
        <auro-button tertiary>Cancel</auro-button>
      </td>
    </tr>
    <tr>
      <td class="upcomingTripFlight">
        <auro-header level="6" margin="top" size="none" display="300">Sun, April 4, 2022</auro-header>
        <auro-flight flights='["AS 110", "AS 12"]' duration="11h 5m" daysChanged="0" departureTime="12:45 am" departureStation="ANC" arrivalTime="3:50 pm" ArrivalStation="BOS">
          <auro-flightline>
            <auro-flight-segment iata="SEA" duration="1h 35m" />
          </auro-flightline>
          <span slot="footer">
            <auro-icon category="logos" name="tail-AS" style="width: 24px" />
            AS110 is subject to government approval <br />
          </span>
        </auro-flight>
      </td>
      <td class="upcomingTripFlightDetails">
        <div class="upcomingTripDetails">
          <div class="upcomingTripTravelers">4 travelers</div>
          <div class="upcomingTripPriority">
            <auro-button onClick="toggleInterruption('#priority')" secondary>Priority: E1Y.14</auro-button>
          </div>
          <div class="upcomingTripType fineprint">Pleasure Space Available (Coach)</div>
        </div>
      </td>
      <td class="upcomingTripConfirmation">zxcvsa</td>
      <td class="upcomingTripCancel">
        <auro-button tertiary>Cancel</auro-button>
      </td>
    </tr>
  </table>
</div>

<style>

  table.upcomingTripData {
    width: 100%;
  }

  table.upcomingTripData td {
    padding: 1rem;
    text-align: left;
  }

  table.upcomingTripData .upcomingTripCancel {
    text-align: center;
  }

  td.upcomingTripFlight {
    width: 50%;
  }

  table.upcomingTripData .upcomingTripConfirmation {
    text-align: center;
  }

  .auro_table,
  .auro-markdown table {
    display: block;
    overflow: scroll;
    width: auto;
    margin-bottom: 2rem;
    border-spacing: 0.75rem;
    border-collapse: collapse;
    font-weight: 100;
  }

  .auro_table tr:nth-child(even),
  .auro-markdown table tr:nth-child(even) {
    background-color: #f8f8f8;
  }

  .auro_table th,
  .auro-markdown table th {
    text-align: left;
    font-weight: 500;
  }

  @media screen and (min-width: 660px) {
    .auro_table,
    .auro-markdown table {
      display: table;
      width: 100%;
    }
  }

  .auro_table thead,
  .auro-markdown table thead {
    border-collapse: collapse;
    border-bottom: 1px solid #dbdbdb;
  }

  .auro_table th,
  .auro-markdown table th,
  .auro_table td,
  .auro-markdown table td {
    padding: 1rem;
  }


  .upcomingTrips {
    margin-bottom: var(--auro-size-xxl);
}
@media screen and (min-width: 1024px) {
    .upcomingTrips {
      padding: 0;
    }
  }
.upcomingTrips td {
    white-space: nowrap;
}

  .upcomingTripDetails auro-icon {
    width: 20px;
  }

  .upcomingTripPriority {
    margin: 1rem 0;
  }

  .upcomingTripFlight {
    width: 100%;
  }

  .container {
    display: block;
    max-width: 1232px;
    margin: auto;
}


</style>
