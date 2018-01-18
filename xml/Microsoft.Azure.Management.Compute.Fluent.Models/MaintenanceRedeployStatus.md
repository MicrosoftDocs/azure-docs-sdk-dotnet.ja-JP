<Type Name="MaintenanceRedeployStatus" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus">
  <TypeSignature Language="C#" Value="public class MaintenanceRedeployStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MaintenanceRedeployStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class MaintenanceRedeployStatus" />
  <TypeSignature Language="F#" Value="type MaintenanceRedeployStatus = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MaintenanceRedeployStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MaintenanceRedeployStatus (Nullable&lt;bool&gt; isCustomerInitiatedMaintenanceAllowed = null, Nullable&lt;DateTime&gt; preMaintenanceWindowStartTime = null, Nullable&lt;DateTime&gt; preMaintenanceWindowEndTime = null, Nullable&lt;DateTime&gt; maintenanceWindowStartTime = null, Nullable&lt;DateTime&gt; maintenanceWindowEndTime = null, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceOperationResultCodeTypes&gt; lastOperationResultCode = null, string lastOperationMessage = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; isCustomerInitiatedMaintenanceAllowed, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; preMaintenanceWindowStartTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; preMaintenanceWindowEndTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; maintenanceWindowStartTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; maintenanceWindowEndTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceOperationResultCodeTypes&gt; lastOperationResultCode, string lastOperationMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.#ctor(System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceOperationResultCodeTypes},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional isCustomerInitiatedMaintenanceAllowed As Nullable(Of Boolean) = null, Optional preMaintenanceWindowStartTime As Nullable(Of DateTime) = null, Optional preMaintenanceWindowEndTime As Nullable(Of DateTime) = null, Optional maintenanceWindowStartTime As Nullable(Of DateTime) = null, Optional maintenanceWindowEndTime As Nullable(Of DateTime) = null, Optional lastOperationResultCode As Nullable(Of MaintenanceOperationResultCodeTypes) = null, Optional lastOperationMessage As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus : Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceOperationResultCodeTypes&gt; * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus (isCustomerInitiatedMaintenanceAllowed, preMaintenanceWindowStartTime, preMaintenanceWindowEndTime, maintenanceWindowStartTime, maintenanceWindowEndTime, lastOperationResultCode, lastOperationMessage)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="isCustomerInitiatedMaintenanceAllowed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="preMaintenanceWindowStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="preMaintenanceWindowEndTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maintenanceWindowStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maintenanceWindowEndTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastOperationResultCode" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceOperationResultCodeTypes&gt;" />
        <Parameter Name="lastOperationMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="isCustomerInitiatedMaintenanceAllowed">To be added.</param>
        <param name="preMaintenanceWindowStartTime">To be added.</param>
        <param name="preMaintenanceWindowEndTime">To be added.</param>
        <param name="maintenanceWindowStartTime">To be added.</param>
        <param name="maintenanceWindowEndTime">To be added.</param>
        <param name="lastOperationResultCode">To be added.</param>
        <param name="lastOperationMessage">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCustomerInitiatedMaintenanceAllowed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsCustomerInitiatedMaintenanceAllowed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsCustomerInitiatedMaintenanceAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.IsCustomerInitiatedMaintenanceAllowed" />
      <MemberSignature Language="VB.NET" Value="Public Property IsCustomerInitiatedMaintenanceAllowed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsCustomerInitiatedMaintenanceAllowed : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.IsCustomerInitiatedMaintenanceAllowed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isCustomerInitiatedMaintenanceAllowed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOperationMessage">
      <MemberSignature Language="C#" Value="public string LastOperationMessage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastOperationMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.LastOperationMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property LastOperationMessage As String" />
      <MemberSignature Language="F#" Value="member this.LastOperationMessage : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.LastOperationMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastOperationMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOperationResultCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceOperationResultCodeTypes&gt; LastOperationResultCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceOperationResultCodeTypes&gt; LastOperationResultCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.LastOperationResultCode" />
      <MemberSignature Language="VB.NET" Value="Public Property LastOperationResultCode As Nullable(Of MaintenanceOperationResultCodeTypes)" />
      <MemberSignature Language="F#" Value="member this.LastOperationResultCode : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceOperationResultCodeTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.LastOperationResultCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastOperationResultCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceOperationResultCodeTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaintenanceWindowEndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; MaintenanceWindowEndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; MaintenanceWindowEndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.MaintenanceWindowEndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaintenanceWindowEndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.MaintenanceWindowEndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.MaintenanceWindowEndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maintenanceWindowEndTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaintenanceWindowStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; MaintenanceWindowStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; MaintenanceWindowStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.MaintenanceWindowStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaintenanceWindowStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.MaintenanceWindowStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.MaintenanceWindowStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maintenanceWindowStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreMaintenanceWindowEndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreMaintenanceWindowEndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreMaintenanceWindowEndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.PreMaintenanceWindowEndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreMaintenanceWindowEndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreMaintenanceWindowEndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.PreMaintenanceWindowEndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preMaintenanceWindowEndTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreMaintenanceWindowStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreMaintenanceWindowStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreMaintenanceWindowStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.PreMaintenanceWindowStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreMaintenanceWindowStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreMaintenanceWindowStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.MaintenanceRedeployStatus.PreMaintenanceWindowStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preMaintenanceWindowStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>