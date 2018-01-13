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
            アプリケーション ゲートウェイの更新を許可する要求のルーティング規則の変更の段階です。
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
        <param name="name">要求のルーティング規則の一意の名前。</param>
        <summary>
            このアプリケーション ゲートウェイの要求ルーティング ルールの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>要求のルーティング規則の最初の段階です。</return>
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
        <param name="name">既存の要求ルーティング ルールの名前。</param>
        <summary>
            要求のルーティング規則の更新を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>要求ルーティング ルールの更新または要求されたルールが存在しない場合は null の最初の段階です。</return>
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
        <param name="name">削除する要求のルーティング規則の名前。</param>
        <summary>
            アプリケーション ゲートウェイからの要求のルーティング規則を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>