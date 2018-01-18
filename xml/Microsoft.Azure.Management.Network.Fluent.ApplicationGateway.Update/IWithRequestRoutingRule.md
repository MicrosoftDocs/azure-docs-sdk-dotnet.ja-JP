<Type Name="IWithRequestRoutingRule" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithRequestRoutingRule">
  <TypeSignature Language="C#" Value="public interface IWithRequestRoutingRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRequestRoutingRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithRequestRoutingRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRequestRoutingRule" />
  <TypeSignature Language="F#" Value="type IWithRequestRoutingRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c15ce-101">アプリケーション ゲートウェイの更新を許可する要求のルーティング規則の変更の段階です。</span><span class="sxs-lookup"><span data-stu-id="c15ce-101">The stage of an application gateway update allowing to modify request routing rules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRequestRoutingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineRequestRoutingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineRequestRoutingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithRequestRoutingRule.DefineRequestRoutingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRequestRoutingRule (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRequestRoutingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithRequestRoutingRule.DefineRequestRoutingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c15ce-102">要求のルーティング規則の一意の名前。</span><span class="sxs-lookup"><span data-stu-id="c15ce-102">A unique name for the request routing rule.</span></span></param>
        <summary>
            <span data-ttu-id="c15ce-103">このアプリケーション ゲートウェイの要求ルーティング ルールの定義を開始します。</span><span class="sxs-lookup"><span data-stu-id="c15ce-103">Begins the definition of a request routing rule for this application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c15ce-104">要求のルーティング規則の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="c15ce-104">The first stage of the request routing rule.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateRequestRoutingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate UpdateRequestRoutingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate UpdateRequestRoutingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithRequestRoutingRule.UpdateRequestRoutingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRequestRoutingRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateRequestRoutingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate" Usage="iWithRequestRoutingRule.UpdateRequestRoutingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c15ce-105">既存の要求ルーティング ルールの名前。</span><span class="sxs-lookup"><span data-stu-id="c15ce-105">The name of an existing request routing rule.</span></span></param>
        <summary>
            <span data-ttu-id="c15ce-106">要求のルーティング規則の更新を開始します。</span><span class="sxs-lookup"><span data-stu-id="c15ce-106">Begins the update of a request routing rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c15ce-107">要求ルーティング ルールの更新または要求されたルールが存在しない場合は null の最初の段階です。</span><span class="sxs-lookup"><span data-stu-id="c15ce-107">The first stage of a request routing rule update or null if the requested rule does not exist.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRequestRoutingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutRequestRoutingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutRequestRoutingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithRequestRoutingRule.WithoutRequestRoutingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRequestRoutingRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRequestRoutingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithRequestRoutingRule.WithoutRequestRoutingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c15ce-108">削除する要求のルーティング規則の名前。</span><span class="sxs-lookup"><span data-stu-id="c15ce-108">The name of the request routing rule to remove.</span></span></param>
        <summary>
            <span data-ttu-id="c15ce-109">アプリケーション ゲートウェイからの要求のルーティング規則を削除します。</span><span class="sxs-lookup"><span data-stu-id="c15ce-109">Removes a request routing rule from the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c15ce-110">更新プログラムの次のステージ。</span><span class="sxs-lookup"><span data-stu-id="c15ce-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>