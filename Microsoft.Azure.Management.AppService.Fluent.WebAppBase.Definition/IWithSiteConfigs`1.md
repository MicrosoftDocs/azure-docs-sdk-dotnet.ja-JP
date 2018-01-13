<Type Name="IWithSiteConfigs&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSiteConfigs&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSiteConfigs`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSiteConfigs(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithSiteConfigs&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT">リソースの型。</typeparam>
    <summary>
            設定するには、その他の構成を許可する、web アプリ定義段階です。 作成または配置スロットとスワップときに、これらの構成を複製することができます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAutoSwapSlotName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithAutoSwapSlotName (string slotName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithAutoSwapSlotName(string slotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithAutoSwapSlotName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAutoSwapSlotName (slotName As String) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAutoSwapSlotName : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithAutoSwapSlotName slotName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="slotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="slotName">スロット、または '運用' を自動スワップの名前。</param>
        <summary>
            この web アプリの展開が完了したときに、自動スワップ スロット名を指定またはデプロイ スロット。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithDefaultDocument">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithDefaultDocument (string document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithDefaultDocument(string document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithDefaultDocument(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDefaultDocument (document As String) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDefaultDocument : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithDefaultDocument document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="document">既定のドキュメントです。</param>
        <summary>
            既定のドキュメントを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithDefaultDocuments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithDefaultDocuments (System.Collections.Generic.IList&lt;string&gt; documents);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithDefaultDocuments(class System.Collections.Generic.IList`1&lt;string&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithDefaultDocuments(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDefaultDocuments (documents As IList(Of String)) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDefaultDocuments : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithDefaultDocuments documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="documents">既定のドキュメントの一覧です。</param>
        <summary>
            既定のドキュメントのリストを追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithJavaVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithWebContainer&lt;FluentT&gt; WithJavaVersion (Microsoft.Azure.Management.AppService.Fluent.JavaVersion version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithWebContainer`1&lt;!FluentT&gt; WithJavaVersion(class Microsoft.Azure.Management.AppService.Fluent.JavaVersion version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithJavaVersion(Microsoft.Azure.Management.AppService.Fluent.JavaVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithJavaVersion (version As JavaVersion) As IWithWebContainer(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithJavaVersion : Microsoft.Azure.Management.AppService.Fluent.JavaVersion -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithWebContainer&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithJavaVersion version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithWebContainer&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="Microsoft.Azure.Management.AppService.Fluent.JavaVersion" />
      </Parameters>
      <Docs>
        <param name="version">Java バージョンです。</param>
        <summary>
            Java バージョンを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithManagedPipelineMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithManagedPipelineMode (Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode managedPipelineMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithManagedPipelineMode(valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode managedPipelineMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithManagedPipelineMode(Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode)" />
      <MemberSignature Language="F#" Value="abstract member WithManagedPipelineMode : Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithManagedPipelineMode managedPipelineMode" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="managedPipelineMode" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode" />
      </Parameters>
      <Docs>
        <param name="managedPipelineMode">マネージ パイプライン モードです。</param>
        <summary>
            マネージ パイプライン モードを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithNetFrameworkVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithNetFrameworkVersion (Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithNetFrameworkVersion(class Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithNetFrameworkVersion(Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNetFrameworkVersion (version As NetFrameworkVersion) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNetFrameworkVersion : Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithNetFrameworkVersion version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion" />
      </Parameters>
      <Docs>
        <param name="version">.NET Framework のバージョン。</param>
        <summary>
            .NET Framework のバージョンを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDefaultDocument">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithoutDefaultDocument (string document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithoutDefaultDocument(string document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithoutDefaultDocument(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDefaultDocument (document As String) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutDefaultDocument : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithoutDefaultDocument document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="document">既定のドキュメントを削除します。</param>
        <summary>
            既定のドキュメントを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPhp">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithoutPhp ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithoutPhp() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithoutPhp" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPhp () As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutPhp : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithoutPhp " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            PHP サポートを無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPhpVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithPhpVersion (Microsoft.Azure.Management.AppService.Fluent.PhpVersion version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithPhpVersion(class Microsoft.Azure.Management.AppService.Fluent.PhpVersion version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithPhpVersion(Microsoft.Azure.Management.AppService.Fluent.PhpVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPhpVersion (version As PhpVersion) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPhpVersion : Microsoft.Azure.Management.AppService.Fluent.PhpVersion -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithPhpVersion version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="Microsoft.Azure.Management.AppService.Fluent.PhpVersion" />
      </Parameters>
      <Docs>
        <param name="version">PHP のバージョン。</param>
        <summary>
            PHP のバージョンを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPlatformArchitecture">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithPlatformArchitecture (Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture platform);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithPlatformArchitecture(valuetype Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture platform) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithPlatformArchitecture(Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPlatformArchitecture (platform As PlatformArchitecture) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPlatformArchitecture : Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithPlatformArchitecture platform" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="platform" Type="Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture" />
      </Parameters>
      <Docs>
        <param name="platform">プラットフォーム アーキテクチャです。</param>
        <summary>
            使用するプラットフォーム アーキテクチャを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithPythonVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithPythonVersion (Microsoft.Azure.Management.AppService.Fluent.PythonVersion version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithPythonVersion(class Microsoft.Azure.Management.AppService.Fluent.PythonVersion version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithPythonVersion(Microsoft.Azure.Management.AppService.Fluent.PythonVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPythonVersion (version As PythonVersion) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPythonVersion : Microsoft.Azure.Management.AppService.Fluent.PythonVersion -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithPythonVersion version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="Microsoft.Azure.Management.AppService.Fluent.PythonVersion" />
      </Parameters>
      <Docs>
        <param name="version">Python のバージョン。</param>
        <summary>
            Python のバージョンを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRemoteDebuggingDisabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithRemoteDebuggingDisabled ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithRemoteDebuggingDisabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithRemoteDebuggingDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRemoteDebuggingDisabled () As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRemoteDebuggingDisabled : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithRemoteDebuggingDisabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            リモート デバッグを無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithRemoteDebuggingEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithRemoteDebuggingEnabled (Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion remoteVisualStudioVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithRemoteDebuggingEnabled(class Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion remoteVisualStudioVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithRemoteDebuggingEnabled(Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion)" />
      <MemberSignature Language="F#" Value="abstract member WithRemoteDebuggingEnabled : Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithRemoteDebuggingEnabled remoteVisualStudioVersion" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remoteVisualStudioVersion" Type="Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion" />
      </Parameters>
      <Docs>
        <param name="remoteVisualStudioVersion">リモート デバッグ用の Visual Studio のバージョン。</param>
        <summary>
            リモート デバッグ用の Visual Studio のバージョンを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithWebAppAlwaysOn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithWebAppAlwaysOn (bool alwaysOn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithWebAppAlwaysOn(bool alwaysOn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithWebAppAlwaysOn(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWebAppAlwaysOn (alwaysOn As Boolean) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithWebAppAlwaysOn : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithWebAppAlwaysOn alwaysOn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="alwaysOn" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="alwaysOn">True の場合は、web アプリは、常に電源をオンにします。</param>
        <summary>
            かどうか、web アプリの電源オン、VM は常に電源をオンを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
    <Member MemberName="WithWebSocketsEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithWebSocketsEnabled (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithWebSocketsEnabled(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithSiteConfigs`1.WithWebSocketsEnabled(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWebSocketsEnabled (enabled As Boolean) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithWebSocketsEnabled : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithWebSocketsEnabled enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled">Web ソケットが有効になっている場合は true。</param>
        <summary>
            Web ソケットが有効になっているかどうかを指定します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>定義の次のステージ。</return>
      </Docs>
    </Member>
  </Members>
</Type>