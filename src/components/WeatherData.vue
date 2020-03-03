<template>
    <div class="container">      
      <div class="wrapper">
        <header>
          <h1>Weather Forecast</h1>
        </header>

        <div class="weather-main">
          <div class="day-header">
            <h2>Saturday, March 7</h2>
          </div>

          <div class="hour-card">
            <p class="time-of-day">Midnight</p>
            <p class="temp">
              <WeatherIcon icon="night-cloudy" class="night-blue" />
              <span class="feels-like">50&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">2a</p>
            <p class="temp">
              <WeatherIcon icon="night-cloudy" class="night-blue" />
              <span class="feels-like">47&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">4a</p>
            <p class="temp">
              <WeatherIcon icon="night-partly-cloudy" class="night-blue" />
              <span class="feels-like">40&#8457;</span>
            </p>
            <p class="status">Partly Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">6a</p>
            <p class="temp">
              <WeatherIcon icon="night-partly-cloudy" class="night-blue" />
              <span class="feels-like">46&#8457;</span>
            </p>
            <p class="status">Partly Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">8a</p>
            <p class="temp">
              <WeatherIcon icon="cloudy" class="night-blue" />
              <span class="feels-like">65&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">10a</p>
            <p class="temp">
              <WeatherIcon icon="cloudy" class="night-blue" />
              <span class="feels-like">74&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">Noon</p>
            <p class="temp">
              <WeatherIcon icon="cloudy" class="night-blue" />
              <span class="feels-like">80&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">2p</p>
            <p class="temp">
              <WeatherIcon icon="cloudy" class="night-blue" />
              <span class="feels-like">84&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">4p</p>
            <p class="temp">
              <WeatherIcon icon="day-sunny" class="day-yellow" />
              <span class="feels-like">86&#8457;</span>
            </p>
            <p class="status">Sunny</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">6p</p>
            <p class="temp">
              <WeatherIcon icon="day-sunny" class="day-yellow" />
              <span class="feels-like">87&#8457;</span>
            </p>
            <p class="status">Sunny</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">8p</p>
            <p class="temp">
              <WeatherIcon icon="night-clear" class="night-blue" />
              <span class="feels-like">84&#8457;</span>
            </p>
            <p class="status">Clear</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">10p</p>
            <p class="temp">
              <WeatherIcon icon="night-clear" class="night-blue" />
              <span class="feels-like">76&#8457;</span>
            </p>
            <p class="status">Clear</p>
          </div>

          <div class="day-header">
            <h2>Sunday, March 8</h2>
          </div>
          
          <div class="hour-card">
            <p class="time-of-day">Midnight</p>
            <p class="temp">
              <WeatherIcon icon="night-cloudy" class="night-blue" />
              <span class="feels-like">50&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">2a</p>
            <p class="temp">
              <WeatherIcon icon="night-cloudy" class="night-blue" />
              <span class="feels-like">47&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">4a</p>
            <p class="temp">
              <WeatherIcon icon="night-partly-cloudy" class="night-blue" />
              <span class="feels-like">40&#8457;</span>
            </p>
            <p class="status">Partly Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">6a</p>
            <p class="temp">
              <WeatherIcon icon="night-partly-cloudy" class="night-blue" />
              <span class="feels-like">46&#8457;</span>
            </p>
            <p class="status">Partly Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">8a</p>
            <p class="temp">
              <WeatherIcon icon="cloudy" class="night-blue" />
              <span class="feels-like">65&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">10a</p>
            <p class="temp">
              <WeatherIcon icon="cloudy" class="night-blue" />
              <span class="feels-like">74&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">Noon</p>
            <p class="temp">
              <WeatherIcon icon="cloudy" class="night-blue" />
              <span class="feels-like">80&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">2p</p>
            <p class="temp">
              <WeatherIcon icon="cloudy" class="night-blue" />
              <span class="feels-like">84&#8457;</span>
            </p>
            <p class="status">Cloudy</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">4p</p>
            <p class="temp">
              <WeatherIcon icon="day-sunny" class="day-yellow" />
              <span class="feels-like">86&#8457;</span>
            </p>
            <p class="status">Sunny</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">6p</p>
            <p class="temp">
              <WeatherIcon icon="day-sunny" class="day-yellow" />
              <span class="feels-like">87&#8457;</span>
            </p>
            <p class="status">Sunny</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">8p</p>
            <p class="temp">
              <WeatherIcon icon="night-clear" class="night-blue" />
              <span class="feels-like">84&#8457;</span>
            </p>
            <p class="status">Clear</p>
          </div>

          <div class="hour-card">
            <p class="time-of-day">10p</p>
            <p class="temp">
              <WeatherIcon icon="night-clear" class="night-blue" />
              <span class="feels-like">76&#8457;</span>
            </p>
            <p class="status">Clear</p>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
import WeatherIcon from 'vue-weathericons';

export default {
  components: { WeatherIcon }
}
</script>

<style>
body {
  background: #eee;

  font-size: 24px;
}

.container {
  display: flex;
  flex-direction: column;
}

.wrapper {
  width: 100%;
  margin: 1rem auto;
}

header {
  text-align: center;
  margin: 0 1rem 1rem;
}

header h1 {
  margin: 0;
  color: #2b6cb0;
  font-weight: 400;
  font-size: 1.7rem;
  text-transform: uppercase;
}

.day-header {
  margin: 0 1rem 1rem;
  text-align: center;
}

.day-header h2 {
  margin: 0;
  padding: 0.5rem;
  color: #777;
  background-color: #eee;
  font-weight: 400;
  font-size: 1rem;
  text-transform: uppercase;
}

.weather-main {
  margin: 0 1rem;
  border: 1px solid #ddd;
  background: white;
  padding: 1rem 0 0;
}

.hour-card {
  text-align: center;
  border-bottom: 1px solid #ddd;
  padding-bottom: .5rem;
}

.time-of-day {
  font-weight: 600;
  color: #555;
  font-size: 20px;
  margin-bottom: 0;
}

.temp {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: .5rem 0 .25rem;
}

.feels-like {
  margin-left: 0.25rem;
}

.night-blue {
  color: #2b6cb0;
}

.day-yellow {
  color: #ecc94b;
}

.status {
  color: #777;
  text-transform: uppercase;
  font-size: 14px;
  margin-top: .25rem;
}
</style>
