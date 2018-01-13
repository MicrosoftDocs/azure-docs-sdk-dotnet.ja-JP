<Type Name="IWithFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend">
  <TypeSignature Language="C#" Value="public interface IWithFrontend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend" />
  <TypeSignature Language="F#" Value="type IWithFrontend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            フロント エンド IP 構成の変更を許可するアプリケーション ゲートウェイの更新プログラムの段階です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefinePrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.DefinePrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function DefinePrivateFrontend () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefinePrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithFrontend.DefinePrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            既に存在しない場合は、1 つ作成する、既定のプライベート フロント エンド IP 構成の定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>フロント エンドの定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="DefinePublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.DefinePublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function DefinePublicFrontend () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefinePublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithFrontend.DefinePublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            既に存在しない場合は、1 つ作成する、既定のパブリック フロント エンド IP 構成の定義を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>フロント エンドの定義の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdateFrontend (string frontendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdateFrontend(string frontendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.UpdateFrontend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateFrontend (frontendName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateFrontend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate" Usage="iWithFrontend.UpdateFrontend frontendName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="frontendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="frontendName">既存のフロント エンド IP 構成の名前。</param>
        <summary>
            既存のフロント エンド IP 構成の更新を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>フロント エンド IP 構成の更新の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdatePublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdatePublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.UpdatePublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdatePublicFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdatePublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate" Usage="iWithFrontend.UpdatePublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            存在する場合は、パブリック フロント エンド IP 構成の更新を開始します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>フロント エンドの更新プログラムまたはパブリック フロント エンドが存在しない場合は null の最初の段階です。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontend (string frontendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontend(string frontendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.WithoutFrontend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFrontend (frontendName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFrontend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontend.WithoutFrontend frontendName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="frontendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="frontendName">削除するフロント エンド IP 構成の名前。</param>
        <summary>
            指定したフロント エンド IP 構成を削除します。
            その他の設定によって参照されるフロント エンドを削除すると、アプリケーション ゲートウェイが分割することに注意してください。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.WithoutPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrivateFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontend.WithoutPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アプリケーション ゲートウェイをプライベートすることはできません、つまりその endponts することはできません、仮想ネットワーク内から内部的にアクセスできることを指定します。
            いるプライベート フロント エンドを参照するその他の設定がある場合は、削除することが分割アプリケーション ゲートウェイに注意してください。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.WithoutPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPublicFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontend.WithoutPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アプリケーション ゲートウェイがインターネットに接続する必要がありますされないことを指定します。
            パブリック フロント エンドを参照するその他の設定がある場合は、削除することが分割アプリケーション ゲートウェイに注意してください。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>更新プログラムの次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>