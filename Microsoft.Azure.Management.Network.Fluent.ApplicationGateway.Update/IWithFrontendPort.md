<Type Name="IWithFrontendPort" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            アプリケーション ゲートウェイの更新を許可するフロント エンド ポートを変更する段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort (int portNumber, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort(int32 portNumber, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithFrontendPort(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer, name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithFrontendPort (portNumber, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
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
    <Member MemberName="WithoutFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithoutFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFrontendPort (portNumber As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithoutFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">削除するフロント エンド ポートのポート番号。</param>
        <summary>
            指定したフロント エンド ポートを削除します。
            フロント エンドを削除するその他の設定によって参照されるポートが分割アプリケーション ゲートウェイに注意してください。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithoutFrontendPort(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFrontendPort (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFrontendPort : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithoutFrontendPort name" />
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
        <param name="name">削除するフロント エンド ポートの名前。</param>
        <summary>
            指定したフロント エンド ポートを削除します。
            フロント エンドを削除するその他の設定によって参照されるポートが分割アプリケーション ゲートウェイに注意してください。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>