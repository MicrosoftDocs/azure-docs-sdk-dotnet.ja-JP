<Type Name="IWithFrontendPort" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithFrontendPort">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithFrontendPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            フロント エンド ポートの追加を許可するアプリケーション ゲートウェイ定義の段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithFrontendPort.WithFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithFrontendPort.WithFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">ポート番号です。</param>
        <summary>
            既に存在しない限り、自動生成の名前と、指定したポート番号、フロント エンド ポートを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithFrontendPort (int portNumber, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithFrontendPort(int32 portNumber, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithFrontendPort.WithFrontendPort(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer, name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithFrontendPort.WithFrontendPort (portNumber, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="portNumber">ポート番号です。</param>
        <param name="name">ポートに割り当てる名前。</param>
        <summary>
            既にこの名前、および数に一致するポートが存在しない場合は、指定した名前とポート番号をフロント エンド ポートを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>次のステージの定義、または null の場合は、名前と、番号の両方ではなくはどちらかに一致するポートは既に存在します。</return>
      </Docs>
    </Member>
  </Members>
</Type>