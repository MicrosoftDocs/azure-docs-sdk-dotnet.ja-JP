<Type Name="IWithBackendHttpConfiguration&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackendHttpConfiguration&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendHttpConfiguration`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration`1" />
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
    <typeparam name="ParentT">この定義をアタッチした後に返される、アプリケーション ゲートウェイの定義の段階です。</typeparam>
    <summary>
            Application gateway のステージでは、ルーティング ルールの定義にルーティング規則を関連付けるにはバックエンド HTTP 設定の構成を指定する許可を要求します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;ParentT&gt; ToBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress`1&lt;!ParentT&gt; ToBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration`1.ToBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendHttpConfiguration (name As String) As IWithBackendOrAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;'ParentT&gt;" Usage="iWithBackendHttpConfiguration.ToBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">バックエンド HTTP 設定の構成の名前。</param>
        <summary>
            この要求のルーティングの規則に指定されたバックエンド HTTP 設定の構成を関連付けます。
            バックエンド構成がまだ存在しない場合は、defineBackendHttpConfiguration(...) を使用して、アプリケーション ゲートウェイ定義のオプションの一部で定義する必要があります。要求のルーティングの規則は、名前のみでそれを参照します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="ToBackendHttpPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;ParentT&gt; ToBackendHttpPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress`1&lt;!ParentT&gt; ToBackendHttpPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration`1.ToBackendHttpPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendHttpPort (portNumber As Integer) As IWithBackendOrAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendHttpPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;'ParentT&gt;" Usage="iWithBackendHttpConfiguration.ToBackendHttpPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">新しいバックエンド HTTP 設定の構成用のポート番号。</param>
        <summary>
            指定されたバックエンド ポートと HTTP プロトコルのバックエンド HTTP 設定の構成を作成し、この要求のルーティング規則と関連付けます。
            自動生成の名前は、この構成を新しく作成されたため使用されます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>