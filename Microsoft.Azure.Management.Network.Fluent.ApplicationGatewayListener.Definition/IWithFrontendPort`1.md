<Type Name="IWithFrontendPort&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">この定義をアタッチした後に戻るには、親アプリケーション ゲートウェイ定義の段階です。</typeparam>
    <summary>
            リスナーを関連付けるには、フロント エンド ポートを指定できるようにアプリケーション ゲートウェイ フロント エンド リスナー定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;ParentT&gt; WithFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach`1&lt;!ParentT&gt; WithFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort`1.WithFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithFrontendPort.WithFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">ポート番号です。</param>
        <summary>
            指定したフロント エンド ポート番号でリッスンするリスナーを有効にします。
            このポート番号のフロント エンド ポートがまだ存在しない場合、新しい作成されます自動生成される名前。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;ParentT&gt; WithFrontendPort (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach`1&lt;!ParentT&gt; WithFrontendPort(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithFrontendPort`1.WithFrontendPort(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (name As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithFrontendPort.WithFrontendPort name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">既存のフロント エンド ポートの名前。</param>
        <summary>
            指定した既存のフロント エンド ポートでリッスンするリスナーを有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>