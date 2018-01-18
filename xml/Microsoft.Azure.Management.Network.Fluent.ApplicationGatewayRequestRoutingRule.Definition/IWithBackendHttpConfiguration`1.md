<Type Name="IWithBackendHttpConfiguration&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendHttpConfiguration&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackendHttpConfiguration&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendHttpConfiguration`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendHttpConfiguration`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendHttpConfiguration(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithBackendHttpConfiguration&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="86ef3-101">この定義をアタッチした後に返される、アプリケーション ゲートウェイの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="86ef3-101">The stage of the application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="86ef3-102">Application gateway のステージでは、ルーティング ルールの定義にルーティング規則を関連付けるにはバックエンド HTTP 設定の構成を指定する許可を要求します。</span><span class="sxs-lookup"><span data-stu-id="86ef3-102">The stage of an application gateway request routing rule definition allowing to specify the backend HTTP settings configuration to associate the routing rule with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;ParentT&gt; ToBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress`1&lt;!ParentT&gt; ToBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendHttpConfiguration`1.ToBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendHttpConfiguration (name As String) As IWithBackendOrAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;'ParentT&gt;" Usage="iWithBackendHttpConfiguration.ToBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="86ef3-103">バックエンド HTTP 設定の構成の名前。</span><span class="sxs-lookup"><span data-stu-id="86ef3-103">The name of a backend HTTP settings configuration.</span></span></param>
        <summary>
            <span data-ttu-id="86ef3-104">この要求のルーティングの規則に指定されたバックエンド HTTP 設定の構成を関連付けます。</span><span class="sxs-lookup"><span data-stu-id="86ef3-104">Associates the specified backend HTTP settings configuration with this request routing rule.</span></span>
            <span data-ttu-id="86ef3-105">バックエンド構成がまだ存在しない場合は、defineBackendHttpConfiguration(...) を使用して、アプリケーション ゲートウェイ定義のオプションの一部で定義する必要があります。要求のルーティングの規則は、名前のみでそれを参照します。</span><span class="sxs-lookup"><span data-stu-id="86ef3-105">If the backend configuration does not exist yet, it must be defined in the optional part of the application gateway definition, using  defineBackendHttpConfiguration(...). The request routing rule references it only by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="86ef3-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="86ef3-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ToBackendHttpPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;ParentT&gt; ToBackendHttpPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress`1&lt;!ParentT&gt; ToBackendHttpPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendHttpConfiguration`1.ToBackendHttpPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendHttpPort (portNumber As Integer) As IWithBackendOrAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendHttpPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;'ParentT&gt;" Usage="iWithBackendHttpConfiguration.ToBackendHttpPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber"><span data-ttu-id="86ef3-107">新しいバックエンド HTTP 設定の構成用のポート番号。</span><span class="sxs-lookup"><span data-stu-id="86ef3-107">The port number for a new backend HTTP settings configuration.</span></span></param>
        <summary>
            <span data-ttu-id="86ef3-108">指定されたバックエンド ポートと HTTP プロトコルのバックエンド HTTP 設定の構成を作成し、この要求のルーティング規則と関連付けます。</span><span class="sxs-lookup"><span data-stu-id="86ef3-108">Creates a backend HTTP settings configuration for the specified backend port and the HTTP protocol, and associates it with this request routing rule.</span></span>
            <span data-ttu-id="86ef3-109">自動生成の名前は、この構成を新しく作成されたため使用されます。</span><span class="sxs-lookup"><span data-stu-id="86ef3-109">An auto-generated name will be used for this newly created configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="86ef3-110">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="86ef3-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>