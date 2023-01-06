---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    id: skills
    content:
      title: Skills
      items:
        - icon: "embedded-c"
          icon_pack: "custom"
          name: "Embedded Computing"
          description: "Embedded Computing in C"
        - icon: "IoT"
          icon_pack: "custom"
          name: "IoT"
          description: "IoT design systems"
        - icon: "machine-learning"
          icon_pack: "custom"
          name: "Machine Learning"
          description: "Machine Learning on Embedded devices"
        - icon: "hci"
          icon_pack: "custom"
          name: "HCI Research"
          description: "Academic research in HCI field"
        - icon: "agile"
          icon_pack: "custom"
          name: "Agile"
          description: "Agile Development Method"
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
          - title: Thesis worker, pipline Leakage dectection
            company: Oras Group
            company_url: 'https://www.orasgroup.com'
            company_logo: oras_logo
            location: Rauma
            date_start: '2022-05-01'
            date_end: '2022-12-31'
            description: '
              Responsibility include:

              - Find a feasible solution for implementing intelligence into existing water valve in homes pipeline.

              - Program Silab’s EFR32 controller to collect hydraulic measurements from the pipeline (pressure, flowrate, temperature)

              - Collaborate with experts in the water laboratory to design a pilot pipeline.

              - Applied hydraulic theories (transient analysis) in detecting abnormal behaviors in the pipeline.

              - Develop a machine learning model using Scikit-learn module to detect and localize leaks'

          - title: Visiting research Assistant
            company: TIERS research group
            company_url: 'https://tiers.utu.fi'
            company_logo: turku
            location: Turku
            date_start: '2019-12-17'
            date_end: '2020-03-31'
            description: '
              Responsibility include: 

              - Perform quantitative research regarding the daily life activity monitoring systems that targeted elderly.

              - Build a smart system for controlling actuators based on EMG signals from myo-electric armband.

              - Calibrate recognized gesture signals and collected IMU data (acceleration, angular velocity) to control robotic Arm.'

          - title: Front-end web developer
            company: TheFirma
            company_url: ''
            company_logo: thefirma
            location: Turku
            date_start: '2018-06-11'
            date_end: '2020-08-28'
            description: '
              Responsibility include: 

              - Co-designed, co-developed and implemented a prototype mobile web-App in a team with the project owner.

              - Used React/Redux, Semantic UI, and related software packages for building user interface.

              - Integrated with Django API on the frontend to display relevant data.'
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org/account/accomplishments/specialization/certificate/KPGYGF4SDYD9
          date_end: ''
          date_start: '2022-07-08'
          description: "
            Course content:
            
            - Build and train deep neural networks, identify key architecture parameters, implement vectorized neural networks and deep learning to applications

            - Train test sets, analyze variance for DL applications, use standard techniques and optimization algorithms, and build neural networks in TensorFlow

            - Build a CNN and apply it to detection and recognition tasks, use neural style transfer to generate art, and apply algorithms to image and video data

            - Build and train RNNs, work with NLP and Word Embeddings, and use HuggingFace tokenizers and transformer models to perform NER and Question Answering"
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Deep Learning Specialization
          url: 'https://www.coursera.org/account/accomplishments/specialization/KPGYGF4SDYD9'
        - certificate_url: https://www.udemy.com/certificate/UC-4a6b5e3c-1dfa-4c7c-913d-1e83a1f386be/
          date_end: ''
          date_start: '2021-12-31'
          description: "This course Demystifies the internal working of the Microcontroller and its Peripherals. Coding for the Peripherals STEP-BY-STEP and Developing software drivers entirely from scratch by extracting maximum information from Datasheets, Reference manuals, specs, etc. Protocol Decoding Using logic analyzers, Debugging, Testing along with Hints and Tips."
          organization: Udemy
          organization_url: https://www.udemy.com
          title: Mastering Microcontroller and Embedded Driver Development
          url: 'https://www.udemy.com/course/mastering-microcontroller-with-peripheral-driver-development/'
        - certificate_url: https://matlabacademy.mathworks.com/progress/share/certificate.html?id=2bd8673d-3454-452b-ae8b-8050a16134f1&
          date_end: ''
          date_start: '2022-02-12'
          description: 'Learn core MATLAB® functionality for data analysis, visualization, modeling, and programming. Implement a common data analysis workflow that can be applied to many science and engineering applications.'
          organization: MathWorks
          organization_url: https://matlabacademy.mathworks.com
          title: Mathlab Fundamentals
          url: 'https://matlabacademy.mathworks.com/details/matlab-fundamentals/mlbe'
        - certificate_url: https://drive.google.com/file/d/1FDbmnmR21C9ra1drc6CPJEBhLFd1ktnp/view?usp=sharing
          date_end: ''
          date_start: '2020-06-03'
          description: '
            - The curriculum consists of basic, professional and optional studies as well as practical training and a Bachelor’s thesis project. 

            - Basic studies contain fundamentals of science and ICT, language and communication courses, and coaching in study skills. Basic studies take place during the first and second study year, and they guide you into the topics of your future professional field. Professional studies focus mainly on more advanced topics in our ICT competence tracks and their applications, as well as business and entrepreneurship topics. Professional studies start in the second year and continue to the second last semester.

            - <strong>Specialization: Embedded Software and IoT </strong>focuses on design and implementation of network-connected microcontroller systems such as fitness devices, mobile  hones, robots, and future vehicles. The studies include both hardware and software design in wired and wireless environments. Graduated students are typically employed in product development tasks in industry.'
          organization: TurkuAMK
          organization_url: https://www.tuas.fi/en
          title: Bachelor of Engineering, Information Communication Technology
          url: 'https://www.tuas.fi/en/study-tuas/degree-programmes/bachelor-engineering-information-technology/'
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: HMI
          tag: HMI
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: minh.nguyen@tuni.fi
      office_hours:
        - 'Monday-Friday 10:00 to 16:00'
      contact_links:
        - icon: whatsapp
          icon_pack: fab
          name: DM
          link: 'https://web.whatsapp.com'
        - icon: telegram
          icon_pack: fab
          name: '@minh_nguy3n'
          link: 'https://web.telegram.im'
        - icon: linkedin
          icon_pack: fab
          name: Message Me
          link: 'https://www.linkedin.com/in/minh-nguyen3195/'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
