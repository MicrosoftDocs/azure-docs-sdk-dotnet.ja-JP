<Type Name="ComposeDeploymentStatusQueryDescription" FullName="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentStatusQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentStatusQueryDescription" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentStatusQueryDescription = class" />
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
      <para>System.Fabric.FabricClient.ComposeDeploymentClient.GetComposeDeploymentStatusPagedListAsync(Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription) で使用されるクエリの入力を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComposeDeploymentStatusQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>インスタンスをインスタンス化<see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />クラスです。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.ContinuationToken" />
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
          <para>取得または次のページを取得するクエリで使用できるトークンを設定します。</para>
        </summary>
        <value>
          <para>次のページを取得するクエリで使用できるトークンです。</para>
        </value>
        <remarks>
          <para>ContinuationToken は、前のクエリによって受信されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentNameFilter">
      <MemberSignature Language="C#" Value="public string DeploymentNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentNameFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.DeploymentNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentNameFilter : string with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.DeploymentNameFilter" />
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
          <para>取得または設定の名前は、クエリを実行する展開を作成します。</para>
        </summary>
        <value>
          <para>名前は、クエリを実行する展開を作成します。</para>
        </value>
        <remarks>
          <para> 展開を作成すべて DeploymentNameFilter が指定されていない場合が返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public long MaxResults { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxResults As Long" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int64 with get, set" Usage="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはページごとに返されることができます Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems の最大数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            この値が設定されていない場合、返された Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItems の数を制限するのには使用されません。
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>