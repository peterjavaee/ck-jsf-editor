CKJsfEditor is a JSF 2 component for CKEditor (see http://ckeditor.com).  Usage should be simple.  Include the
ck-jsf-editor.jar file in your WEB-INF/lib directory and do include it in your jsf pages as below:

<html xmlns="http://www.w3.org/1999/xhtml"
      xmlns:h="http://java.sun.com/jsf/html"
      xmlns:f="http://java.sun.com/jsf/core"
      xmlns:ck="http://code.google.com/ck-jsf-editor"
      xml:lang="en" lang="en">


now you can use the tag in your page like so:

<ck:editor id="ckEd" value="#{editorTest.editorContents}" width="800px" widgetVar="eduardo" uiColor="#aed0ea"/>


As it is an input component, it must be included in an <h:form> tag.

For more detailed information please see the wiki at: http://code.google.com/p/ck-jsf-editor/w/list

