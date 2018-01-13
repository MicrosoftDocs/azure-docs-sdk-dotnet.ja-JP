<Type Name="IWithListener" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithListener">
  <TypeSignature Language="C#" Value="public interface IWithListener" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithListener" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithListener" />
  <TypeSignature Language="F#" Value="type IWithListener = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            リスナーを追加できるようにアプリケーション ゲートウェイ定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt; DefineListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithListener.DefineListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineListener (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" Usage="iWithListener.DefineListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">リスナーの一意の名前。</param>
        <summary>
            ゲートウェイに接続する新しいアプリケーション ゲートウェイ リスナーの定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>リスナーの定義の最初の段階です。</return>
      </Docs>
    </Member>
  </Members>
</Type>