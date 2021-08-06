
<script lang="ts">
  import { Col, Container, Row } from 'sveltestrap';
</script>

<div class='ripple-background'>
    <div class='circle xxlarge shade1'></div>
    <div class='circle xlarge shade2'></div>
    <div class='circle large shade3'></div>
    <div class='circle mediun shade4'></div>
    <div class='circle small shade5'></div>
</div>

<div id="Main">
    <Container>
        <Row>
          <Col>
              <h1>Greetings reader</h1>
              <p>Welcome to some pages in honor to hard work.</p>
          </Col>
        </Row>
        <Row>
          <Col>
              <h2>Greatness was achieved using</h2>
          </Col>
        </Row>
        <Row>
          <Col>VS Code</Col>
          <Col>Github</Col>
          <Col>Firebase</Col>
          <Col>Svelte</Col>
        </Row>
      </Container>
</div>
