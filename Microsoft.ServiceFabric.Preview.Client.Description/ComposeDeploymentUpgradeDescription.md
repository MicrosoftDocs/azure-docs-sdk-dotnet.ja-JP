<Type Name="ComposeDeploymentUpgradeDescription" FullName="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentUpgradeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentUpgradeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentUpgradeDescription" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentUpgradeDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>使用して作成される compose 展開について説明します<see cref="M:System.Fabric.FabricClient.ComposeDeploymentClient.UpgradeComposeDeploymentAsync(System.Fabric.Description.ComposeDeploymentUpgradeDescriptionWrapper)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComposeDeploymentUpgradeDescription (string deploymentName, string[] composeFilePaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deploymentName, string[] composeFilePaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.#ctor(System.String,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deploymentName As String, composeFilePaths As String())" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription : string * string[] -&gt; Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" Usage="new Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription (deploymentName, composeFilePaths)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="composeFilePaths" Type="System.String[]" />
      </Parameters>
      <Docs>
        <param name="deploymentName">To be added.</param>
        <param name="composeFilePaths">To be added.</param>
        <summary>
            <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" /> の新しいインスタンスを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComposeFilePaths">
      <MemberSignature Language="C#" Value="public string[] ComposeFilePaths { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string[] ComposeFilePaths" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ComposeFilePaths" />
      <MemberSignature Language="VB.NET" Value="Public Property ComposeFilePaths As String()" />
      <MemberSignature Language="F#" Value="member this.ComposeFilePaths : string[] with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ComposeFilePaths" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ファイルのパスは、この展開の次のバージョンについて説明する構成の配列を取得します。</para>
        </summary>
        <value>
          <para>作成するファイルのパスの配列。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistryPassword">
      <MemberSignature Language="C#" Value="public string ContainerRegistryPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRegistryPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ContainerRegistryPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistryPassword As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistryPassword : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ContainerRegistryPassword" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ContainerRegistryUserName パラメーターで指定されたユーザー名に関連付けられているパスワードを取得します。</para>
        </summary>
        <value>
          <para>コンテナー レジストリ パスワードです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistryUserName">
      <MemberSignature Language="C#" Value="public string ContainerRegistryUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRegistryUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ContainerRegistryUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistryUserName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistryUserName : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.ContainerRegistryUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>この展開内のコンテナーのイメージが存在するコンテナー レジストリのユーザー名を取得します。</para>
        </summary>
        <value>
          <para>コンテナー レジストリのユーザー名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentName">
      <MemberSignature Language="C#" Value="public string DeploymentName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.DeploymentName" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentName As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentName : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.DeploymentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アップグレードするのには、作成する展開の名前を取得します。</para>
        </summary>
        <value>
          <para>配置の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRegistryPasswordEncrypted">
      <MemberSignature Language="C#" Value="public bool IsRegistryPasswordEncrypted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRegistryPasswordEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.IsRegistryPasswordEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public Property IsRegistryPasswordEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRegistryPasswordEncrypted : bool with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.IsRegistryPasswordEncrypted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>ContainerRegistryPassword パラメーターで指定されたパスワードが暗号化されている場合を取得します。</para>
        </summary>
        <value>
          <para>レジストリのパスワードが暗号化されている場合は true。 False それ以外の場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradePolicyDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.UpgradePolicyDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradePolicyDescription As UpgradePolicyDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradePolicyDescription : System.Fabric.Description.UpgradePolicyDescription with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription.UpgradePolicyDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradePolicyDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定をアップグレードするためのポリシーの説明の展開を作成します。</para>
        </summary>
        <value>
          <para>これをアップグレードするために使用するポリシーの説明は、展開を作成します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>