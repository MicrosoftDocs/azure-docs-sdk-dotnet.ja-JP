<Type Name="IWithBackend&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackend&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackend&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackend`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackend`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackend(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithBackend&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="5053a-101">この定義をアタッチした後に返される、アプリケーション ゲートウェイの定義の段階です。</span><span class="sxs-lookup"><span data-stu-id="5053a-101">The stage of the application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="5053a-102">Application gateway のステージでは、ルーティング ルールの定義にルーティング規則を関連付けるには、バックエンドの指定を許可するを要求します。</span><span class="sxs-lookup"><span data-stu-id="5053a-102">The stage of an application gateway request routing rule definition allowing to specify the backend to associate the routing rule with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;ParentT&gt; ToBackend (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; ToBackend(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackend`1.ToBackend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackend (name As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithBackend.ToBackend name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5053a-103">既存のバックエンドの名前。</span><span class="sxs-lookup"><span data-stu-id="5053a-103">The name of an existing backend.</span></span></param>
        <summary>
            <span data-ttu-id="5053a-104">このアプリケーション ゲートウェイ上のバックエンドを要求のルーティング規則を関連付けます。</span><span class="sxs-lookup"><span data-stu-id="5053a-104">Associates the request routing rule with a backend on this application gateway.</span></span>
            <span data-ttu-id="5053a-105">バックエンドがまだ存在しない場合は、defineBackend(...) を使用して、アプリケーション ゲートウェイ定義のオプションの一部で定義する必要があります。要求のルーティングの規則は、名前のみでそれを参照します。</span><span class="sxs-lookup"><span data-stu-id="5053a-105">If the backend does not yet exist, it must be defined in the optional part of the application gateway definition, using  defineBackend(...). The request routing rule references it only by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5053a-106">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="5053a-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>