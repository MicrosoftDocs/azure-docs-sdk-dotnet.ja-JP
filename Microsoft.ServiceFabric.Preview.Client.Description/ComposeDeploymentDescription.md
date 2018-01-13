<Type Name="ComposeDeploymentDescription" FullName="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentDescription" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentDescription = class" />
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
      <para>System.Fabric.FabricClient.ComposeDeploymentClient.CreateComposeDeploymentAsync(Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription) を使用して作成される compose 展開について説明します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComposeDeploymentDescription (string deploymentName, string composeFilePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string deploymentName, string composeFilePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deploymentName As String, composeFilePath As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription : string * string -&gt; Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" Usage="new Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription (deploymentName, composeFilePath)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deploymentName" Type="System.String" />
        <Parameter Name="composeFilePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deploymentName">
          <para>名前は、展開を作成します。</para>
        </param>
        <param name="composeFilePath">
          <para>作成するファイルへのパス。</para>
        </param>
        <summary>
          <para>インスタンスをインスタンス化<see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />アプリケーション インスタンス名と、作成するファイルへのパスを使用します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComposeFilePath">
      <MemberSignature Language="C#" Value="public string ComposeFilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComposeFilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ComposeFilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComposeFilePath As String" />
      <MemberSignature Language="F#" Value="member this.ComposeFilePath : string" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ComposeFilePath" />
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
          <para>作成するファイルへのパスを取得します。</para>
        </summary>
        <value>
          <para>作成するファイルのパス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistryPassword">
      <MemberSignature Language="C#" Value="public string ContainerRegistryPassword { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRegistryPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ContainerRegistryPassword" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistryPassword As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistryPassword : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ContainerRegistryPassword" />
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
          <para>コンテナー レジストリ パスワードを取得します。</para>
        </summary>
        <value>
          <para>コンテナー レジストリのユーザーのパスワードです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistryUserName">
      <MemberSignature Language="C#" Value="public string ContainerRegistryUserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRegistryUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ContainerRegistryUserName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistryUserName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistryUserName : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.ContainerRegistryUserName" />
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
          <para>コンテナー レジストリのユーザー名を取得します。</para>
        </summary>
        <value>
          <para>コンテナー レジストリのユーザー名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentName">
      <MemberSignature Language="C#" Value="public string DeploymentName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.DeploymentName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeploymentName As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentName : string" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.DeploymentName" />
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
          <para>作成するデプロイの名前を取得します。</para>
        </summary>
        <value>
          <para>作成する展開の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRegistryPasswordEncrypted">
      <MemberSignature Language="C#" Value="public bool IsRegistryPasswordEncrypted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsRegistryPasswordEncrypted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.IsRegistryPasswordEncrypted" />
      <MemberSignature Language="VB.NET" Value="Public Property IsRegistryPasswordEncrypted As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsRegistryPasswordEncrypted : bool with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription.IsRegistryPasswordEncrypted" />
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
          <para>指定されたレジストリのパスワードを暗号化するかを取得します。</para>
        </summary>
        <value>
          <para>レジストリのパスワードが暗号化されている場合は true。 False それ以外の場合。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>