<Type Name="IWithDockerContainerImage" FullName="Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage">
  <TypeSignature Language="C#" Value="public interface IWithDockerContainerImage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDockerContainerImage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDockerContainerImage" />
  <TypeSignature Language="F#" Value="type IWithDockerContainerImage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Web アプリを指定する許可の docker イメージ ソースを更新します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithBuiltInImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithBuiltInImage (Microsoft.Azure.Management.AppService.Fluent.RuntimeStack runtimeStack);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate WithBuiltInImage(class Microsoft.Azure.Management.AppService.Fluent.RuntimeStack runtimeStack) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage.WithBuiltInImage(Microsoft.Azure.Management.AppService.Fluent.RuntimeStack)" />
      <MemberSignature Language="F#" Value="abstract member WithBuiltInImage : Microsoft.Azure.Management.AppService.Fluent.RuntimeStack -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate" Usage="iWithDockerContainerImage.WithBuiltInImage runtimeStack" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="runtimeStack" Type="Microsoft.Azure.Management.AppService.Fluent.RuntimeStack" />
      </Parameters>
      <Docs>
        <param name="runtimeStack">イメージにインストールされているランタイム スタック。</param>
        <summary>
            いずれかで、作成する docker コンテナー イメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateDockerHubImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials WithPrivateDockerHubImage (string imageAndTag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials WithPrivateDockerHubImage(string imageAndTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage.WithPrivateDockerHubImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateDockerHubImage (imageAndTag As String) As IWithCredentials" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateDockerHubImage : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials" Usage="iWithDockerContainerImage.WithPrivateDockerHubImage imageAndTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageAndTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageAndTag">イメージと省略可能なタグ (たとえば ' イメージ: タグ ')。</param>
        <summary>
            Docker Hub からいずれかに docker コンテナー イメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateRegistryImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials WithPrivateRegistryImage (string imageAndTag, string serverUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials WithPrivateRegistryImage(string imageAndTag, string serverUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage.WithPrivateRegistryImage(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateRegistryImage (imageAndTag As String, serverUrl As String) As IWithCredentials" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateRegistryImage : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials" Usage="iWithDockerContainerImage.WithPrivateRegistryImage (imageAndTag, serverUrl)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageAndTag" Type="System.String" />
        <Parameter Name="serverUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageAndTag">イメージと省略可能なタグ (たとえば ' イメージ: タグ ')。</param>
        <param name="serverUrl">サーバーの URL をプライベート レジストリです。</param>
        <summary>
            プライベート レジストリからいずれかに docker コンテナー イメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicDockerHubImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand WithPublicDockerHubImage (string imageAndTag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand WithPublicDockerHubImage(string imageAndTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithDockerContainerImage.WithPublicDockerHubImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicDockerHubImage (imageAndTag As String) As IWithStartUpCommand" />
      <MemberSignature Language="F#" Value="abstract member WithPublicDockerHubImage : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand" Usage="iWithDockerContainerImage.WithPublicDockerHubImage imageAndTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Update.IWithStartUpCommand</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageAndTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageAndTag">イメージと省略可能なタグ (たとえば ' イメージ: タグ ')。</param>
        <summary>
            Docker Hub からいずれかに docker コンテナー イメージを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Web アプリの更新の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>