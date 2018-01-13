<Type Name="IWithBackend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackend">
  <TypeSignature Language="C#" Value="public interface IWithBackend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackend" />
  <TypeSignature Language="F#" Value="type IWithBackend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e038e-101">アプリケーション ゲートウェイの更新を許可するバックエンドを変更する段階です。</span><span class="sxs-lookup"><span data-stu-id="e038e-101">The stage of an application gateway update allowing to modify backends.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackend.DefineBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineBackend (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithBackend.DefineBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e038e-102">バックエンドの一意の名前。</span><span class="sxs-lookup"><span data-stu-id="e038e-102">A unique name for the backend.</span></span></param>
        <summary>
            <span data-ttu-id="e038e-103">ゲートウェイに接続する新しいアプリケーション ゲートウェイのバックエンドの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="e038e-103">Begins the definition of a new application gateway backend to be attached to the gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e038e-104">バックエンドの定義の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="e038e-104">The first stage of the backend definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate UpdateBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate UpdateBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackend.UpdateBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateBackend (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithBackend.UpdateBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e038e-105">バックエンドの名前です。</span><span class="sxs-lookup"><span data-stu-id="e038e-105">The name of the backend.</span></span></param>
        <summary>
            <span data-ttu-id="e038e-106">このアプリケーション ゲートウェイ上の既存のバックエンドの更新を開始します。</span><span class="sxs-lookup"><span data-stu-id="e038e-106">Begins the update of an existing backend on this application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e038e-107">バックエンドの更新プログラムの最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="e038e-107">The first stage of an update of the backend.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutBackend (string backendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutBackend(string backendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackend.WithoutBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutBackend (backendName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithBackend.WithoutBackend backendName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backendName"><span data-ttu-id="e038e-108">既存のバックエンドでこのアプリケーション ゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="e038e-108">The name of an existing backend on this application gateway.</span></span></param>
        <summary>
            <span data-ttu-id="e038e-109">指定されたバックエンドを削除します。</span><span class="sxs-lookup"><span data-stu-id="e038e-109">Removes the specified backend.</span></span>
            <span data-ttu-id="e038e-110">その他の設定によって参照されるバックエンドを削除すると、アプリケーション ゲートウェイが分割することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="e038e-110">Note that removing a backend referenced by other settings may break the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e038e-111">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e038e-111">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutBackendFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutBackendFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutBackendFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackend.WithoutBackendFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutBackendFqdn (fqdn As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutBackendFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithBackend.WithoutBackendFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn"><span data-ttu-id="e038e-112">完全修飾ドメイン名 (FQDN) です。</span><span class="sxs-lookup"><span data-stu-id="e038e-112">A fully qualified domain name (FQDN).</span></span></param>
        <summary>
            <span data-ttu-id="e038e-113">指定された完全修飾ドメイン名 (FQDN) に任意のバックエンドに関連付けられていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="e038e-113">Ensures the specified fully qualified domain name (FQDN) is not associated with any backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e038e-114">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e038e-114">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutBackendIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutBackendIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutBackendIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackend.WithoutBackendIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutBackendIPAddress (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutBackendIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithBackend.WithoutBackendIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="e038e-115">IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="e038e-115">An IP address.</span></span></param>
        <summary>
            <span data-ttu-id="e038e-116">指定した IP アドレスは、任意のバックエンドに関連付けられていないことを確認します。</span><span class="sxs-lookup"><span data-stu-id="e038e-116">Ensures the specified IP address is not associated with any backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e038e-117">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="e038e-117">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>