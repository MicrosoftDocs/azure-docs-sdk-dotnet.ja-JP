<Type Name="IotHubConnectionStringBuilder" FullName="Microsoft.Azure.Devices.IotHubConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public class IotHubConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IotHubConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.IotHubConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public Class IotHubConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type IotHubConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5917f-101">ユーザーによって設定プロパティに基づいて、IoT Hub サービスの接続文字列を構築します。</span><span class="sxs-lookup"><span data-stu-id="5917f-101">Builds a connection string for the IoT Hub service based on the properties populated by the user.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthenticationMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.IAuthenticationMethod AuthenticationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.IAuthenticationMethod AuthenticationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.IotHubConnectionStringBuilder.AuthenticationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationMethod As IAuthenticationMethod" />
      <MemberSignature Language="F#" Value="member this.AuthenticationMethod : Microsoft.Azure.Devices.IAuthenticationMethod with get, set" Usage="Microsoft.Azure.Devices.IotHubConnectionStringBuilder.AuthenticationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IAuthenticationMethod</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.IotHubConnectionStringBuilder Create (string iotHubConnectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.IotHubConnectionStringBuilder Create(string iotHubConnectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IotHubConnectionStringBuilder.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (iotHubConnectionString As String) As IotHubConnectionStringBuilder" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Devices.IotHubConnectionStringBuilder" Usage="Microsoft.Azure.Devices.IotHubConnectionStringBuilder.Create iotHubConnectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IotHubConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="iotHubConnectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="iotHubConnectionString">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.IotHubConnectionStringBuilder Create (string hostname, Microsoft.Azure.Devices.IAuthenticationMethod authenticationMethod);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.IotHubConnectionStringBuilder Create(string hostname, class Microsoft.Azure.Devices.IAuthenticationMethod authenticationMethod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IotHubConnectionStringBuilder.Create(System.String,Microsoft.Azure.Devices.IAuthenticationMethod)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (hostname As String, authenticationMethod As IAuthenticationMethod) As IotHubConnectionStringBuilder" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.Azure.Devices.IAuthenticationMethod -&gt; Microsoft.Azure.Devices.IotHubConnectionStringBuilder" Usage="Microsoft.Azure.Devices.IotHubConnectionStringBuilder.Create (hostname, authenticationMethod)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IotHubConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="Microsoft.Azure.Devices.IAuthenticationMethod" />
      </Parameters>
      <Docs>
        <param name="hostname">To be added.</param>
        <param name="authenticationMethod">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.IotHubConnectionStringBuilder.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Devices.IotHubConnectionStringBuilder.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IotHubName">
      <MemberSignature Language="C#" Value="public string IotHubName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IotHubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.IotHubConnectionStringBuilder.IotHubName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IotHubName As String" />
      <MemberSignature Language="F#" Value="member this.IotHubName : string" Usage="Microsoft.Azure.Devices.IotHubConnectionStringBuilder.IotHubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKey">
      <MemberSignature Language="C#" Value="public string SharedAccessKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.IotHubConnectionStringBuilder.SharedAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKey : string" Usage="Microsoft.Azure.Devices.IotHubConnectionStringBuilder.SharedAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKeyName">
      <MemberSignature Language="C#" Value="public string SharedAccessKeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.IotHubConnectionStringBuilder.SharedAccessKeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedAccessKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKeyName : string" Usage="Microsoft.Azure.Devices.IotHubConnectionStringBuilder.SharedAccessKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public string SharedAccessSignature { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.IotHubConnectionStringBuilder.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedAccessSignature As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : string" Usage="Microsoft.Azure.Devices.IotHubConnectionStringBuilder.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.IotHubConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="iotHubConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>