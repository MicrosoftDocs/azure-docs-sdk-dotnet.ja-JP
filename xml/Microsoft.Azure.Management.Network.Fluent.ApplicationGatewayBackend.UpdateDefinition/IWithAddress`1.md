<Type Name="IWithAddress&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAddress&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAddress&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddress`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddress(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAddress&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="464cb-101">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="464cb-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="464cb-102">Application gateway のステージでは、バックエンドにアドレスを追加できるように定義をバックアップします。</span><span class="sxs-lookup"><span data-stu-id="464cb-102">The stage of an application gateway backed definition allowing to add an address to the backend.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAddress`1.WithFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFqdn (fqdn As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAddress.WithFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn"><span data-ttu-id="464cb-103">完全修飾ドメイン名 (FQDN) です。</span><span class="sxs-lookup"><span data-stu-id="464cb-103">A fully qualified domain name (FQDN).</span></span></param>
        <summary>
            <span data-ttu-id="464cb-104">バックエンドに指定した既存の完全修飾ドメイン名 (FQDN) を追加します。</span><span class="sxs-lookup"><span data-stu-id="464cb-104">Adds the specified existing fully qualified domain name (FQDN) to the backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="464cb-105">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="464cb-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAddress`1.WithIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPAddress (ipAddress As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAddress.WithIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="464cb-106">IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="464cb-106">An IP address.</span></span></param>
        <summary>
            <span data-ttu-id="464cb-107">バックエンドに指定した既存の IP アドレスを追加します。</span><span class="sxs-lookup"><span data-stu-id="464cb-107">Adds the specified existing IP address to the backend.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="464cb-108">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="464cb-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>