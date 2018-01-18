<Type Name="IWithAddress" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress">
  <TypeSignature Language="C#" Value="public interface IWithAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddress" />
  <TypeSignature Language="F#" Value="type IWithAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="799cf-101">アプリケーション ゲートウェイ バックエンドの更新プログラムをバックエンド アドレスを追加するようにの段階です。</span><span class="sxs-lookup"><span data-stu-id="799cf-101">The stage of an application gateway backend update allowing to add an address to the backend.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFqdn (fqdn As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn"><span data-ttu-id="799cf-102">完全修飾ドメイン名 (FQDN) です。</span><span class="sxs-lookup"><span data-stu-id="799cf-102">A fully qualified domain name (FQDN).</span></span></param>
        <summary>
            <span data-ttu-id="799cf-103">バックエンドに指定した既存の完全修飾ドメイン名 (FQDN) を追加します。</span><span class="sxs-lookup"><span data-stu-id="799cf-103">Adds the specified existing fully qualified domain name (FQDN) to the backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="799cf-104">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="799cf-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPAddress (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="799cf-105">IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="799cf-105">An IP address.</span></span></param>
        <summary>
            <span data-ttu-id="799cf-106">バックエンドに指定した既存の IP アドレスを追加します。</span><span class="sxs-lookup"><span data-stu-id="799cf-106">Adds the specified existing IP address to the backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="799cf-107">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="799cf-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutAddress (Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutAddress(class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithoutAddress(Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAddress (address As ApplicationGatewayBackendAddress) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAddress : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithoutAddress address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="799cf-108">バックエンドに関連付けられている既存のアドレス。</span><span class="sxs-lookup"><span data-stu-id="799cf-108">An existing address currently associated with the backend.</span></span></param>
        <summary>
            <span data-ttu-id="799cf-109">指定されたアドレスは、このバックエンドに関連付けられていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="799cf-109">Ensure the specified address is not associated with this backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="799cf-110">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="799cf-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithoutFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFqdn (fqdn As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithoutFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn"><span data-ttu-id="799cf-111">完全修飾ドメイン名です。</span><span class="sxs-lookup"><span data-stu-id="799cf-111">A fully qualified domain name.</span></span></param>
        <summary>
            <span data-ttu-id="799cf-112">指定された完全修飾ドメイン名 (FQDN) がこのバックエンドに関連付けられていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="799cf-112">Ensures the specified fully qualified domain name (FQDN) is not associated with this backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="799cf-113">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="799cf-113">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithoutIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutIPAddress (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithoutIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="799cf-114">IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="799cf-114">An IP address.</span></span></param>
        <summary>
            <span data-ttu-id="799cf-115">指定した IP アドレスは、このバックエンドに関連付けられていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="799cf-115">Ensures the specified IP address is not associated with this backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="799cf-116">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="799cf-116">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>