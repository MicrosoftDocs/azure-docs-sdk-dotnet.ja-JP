<Type Name="ServiceBusManager" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager">
  <TypeSignature Language="C#" Value="public class ServiceBusManager : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Manager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManagementClient&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManagementClient&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManagementClient&gt;, Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusManager extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.Manager`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManagementClient&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManagementClient&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManagementClient&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManagerBase, class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusManager&#xA;Inherits Manager(Of IServiceBusManagementClient)&#xA;Implements IHasInner(Of IServiceBusManagementClient), IManager(Of IServiceBusManagementClient), IServiceBusManager" />
  <TypeSignature Language="F#" Value="type ServiceBusManager = class&#xA;    inherit Manager&lt;IServiceBusManagementClient&gt;&#xA;    interface IServiceBusManager&#xA;    interface IManager&lt;IServiceBusManagementClient&gt;&#xA;    interface IHasInner&lt;IServiceBusManagementClient&gt;&#xA;    interface IManagerBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Manager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManagementClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager&lt;Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManagementClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d4543-101">エントリは、Azure Service Bus の管理 をポイントします。</span><span class="sxs-lookup"><span data-stu-id="d4543-101">Entry point to Azure Service Bus management.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="d4543-102">(ベータ版: この機能はプレビュー期間中および将来のリリースでは、任意の互換性の期待に関係なく、削除を含む設定を含むライブラリのバージョン番号非下位互換性を保つ方法で変更されるようです)。</span><span class="sxs-lookup"><span data-stu-id="d4543-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.)</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusManager (Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.#ctor(Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager : Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient * string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager" Usage="new Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager (restClient, subscriptionId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient" />
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="restClient">To be added.</param>
        <param name="subscriptionId">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager Authenticate (Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials credentials, string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager Authenticate(class Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials credentials, string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.Authenticate(Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Authenticate (credentials As AzureCredentials, subscriptionId As String) As IServiceBusManager" />
      <MemberSignature Language="F#" Value="static member Authenticate : Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials * string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.Authenticate (credentials, subscriptionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials" />
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="credentials">To be added.</param>
        <param name="subscriptionId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager Authenticate (Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager Authenticate(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.Authenticate(Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient,System.String)" />
      <MemberSignature Language="F#" Value="static member Authenticate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient * string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.Authenticate (restClient, subscriptionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient" />
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="restClient">To be added.</param>
        <param name="subscriptionId">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configure">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.IConfigurable Configure ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager/IConfigurable Configure() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.Configure" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Configure () As ServiceBusManager.IConfigurable" />
      <MemberSignature Language="F#" Value="static member Configure : unit -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.IConfigurable" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.Configure " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager+IConfigurable</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Namespaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespaces Namespaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespaces Namespaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.Namespaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Namespaces As IServiceBusNamespaces" />
      <MemberSignature Language="F#" Value="member this.Namespaces : Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespaces" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.ServiceBusManager.Namespaces" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusManager.Namespaces</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Fluent.IServiceBusNamespaces</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>