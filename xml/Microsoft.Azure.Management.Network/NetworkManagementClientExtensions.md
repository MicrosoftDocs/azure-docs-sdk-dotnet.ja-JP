<Type Name="NetworkManagementClientExtensions" FullName="Microsoft.Azure.Management.Network.NetworkManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.NetworkManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type NetworkManagementClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="27894-101">NetworkManagementClient の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="27894-101">Extension methods for NetworkManagementClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckDnsNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult CheckDnsNameAvailability (this Microsoft.Azure.Management.Network.INetworkManagementClient operations, string location, string domainNameLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult CheckDnsNameAvailability(class Microsoft.Azure.Management.Network.INetworkManagementClient operations, string location, string domainNameLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkManagementClientExtensions.CheckDnsNameAvailability(Microsoft.Azure.Management.Network.INetworkManagementClient,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckDnsNameAvailability (operations As INetworkManagementClient, location As String, domainNameLabel As String) As DnsNameAvailabilityResult" />
      <MemberSignature Language="F#" Value="static member CheckDnsNameAvailability : Microsoft.Azure.Management.Network.INetworkManagementClient * string * string -&gt; Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult" Usage="Microsoft.Azure.Management.Network.NetworkManagementClientExtensions.CheckDnsNameAvailability (operations, location, domainNameLabel)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkManagementClient" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="domainNameLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="27894-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="27894-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="27894-103">ドメイン名の場所です。</span><span class="sxs-lookup"><span data-stu-id="27894-103">The location of the domain name.</span></span>
            </param>
        <param name="domainNameLabel">
            <span data-ttu-id="27894-104">検証するドメイン名。</span><span class="sxs-lookup"><span data-stu-id="27894-104">The domain name to be verified.</span></span> <span data-ttu-id="27894-105">次の正規表現に従ってください: ^ [a-z][a-z0-9-]{1,61}[a-z0-9]$ です。</span><span class="sxs-lookup"><span data-stu-id="27894-105">It must conform to the following regular expression: ^[a-z][a-z0-9-]{1,61}[a-z0-9]$.</span></span>
            </param>
        <summary>
            <span data-ttu-id="27894-106">Cloudapp.azure.com ゾーンで、ドメイン名が使用できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="27894-106">Checks whether a domain name in the cloudapp.azure.com zone is available for use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckDnsNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult&gt; CheckDnsNameAvailabilityAsync (this Microsoft.Azure.Management.Network.INetworkManagementClient operations, string location, string domainNameLabel, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult&gt; CheckDnsNameAvailabilityAsync(class Microsoft.Azure.Management.Network.INetworkManagementClient operations, string location, string domainNameLabel, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.NetworkManagementClientExtensions.CheckDnsNameAvailabilityAsync(Microsoft.Azure.Management.Network.INetworkManagementClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckDnsNameAvailabilityAsync : Microsoft.Azure.Management.Network.INetworkManagementClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult&gt;" Usage="Microsoft.Azure.Management.Network.NetworkManagementClientExtensions.CheckDnsNameAvailabilityAsync (operations, location, domainNameLabel, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.NetworkManagementClientExtensions/&lt;CheckDnsNameAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.DnsNameAvailabilityResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.INetworkManagementClient" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="domainNameLabel" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="27894-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="27894-107">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="27894-108">ドメイン名の場所です。</span><span class="sxs-lookup"><span data-stu-id="27894-108">The location of the domain name.</span></span>
            </param>
        <param name="domainNameLabel">
            <span data-ttu-id="27894-109">検証するドメイン名。</span><span class="sxs-lookup"><span data-stu-id="27894-109">The domain name to be verified.</span></span> <span data-ttu-id="27894-110">次の正規表現に従ってください: ^ [a-z][a-z0-9-]{1,61}[a-z0-9]$ です。</span><span class="sxs-lookup"><span data-stu-id="27894-110">It must conform to the following regular expression: ^[a-z][a-z0-9-]{1,61}[a-z0-9]$.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="27894-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="27894-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="27894-112">Cloudapp.azure.com ゾーンで、ドメイン名が使用できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="27894-112">Checks whether a domain name in the cloudapp.azure.com zone is available for use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>