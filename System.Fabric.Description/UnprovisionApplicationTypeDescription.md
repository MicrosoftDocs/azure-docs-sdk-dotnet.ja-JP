<Type Name="UnprovisionApplicationTypeDescription" FullName="System.Fabric.Description.UnprovisionApplicationTypeDescription">
  <TypeSignature Language="C#" Value="public sealed class UnprovisionApplicationTypeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UnprovisionApplicationTypeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.UnprovisionApplicationTypeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UnprovisionApplicationTypeDescription" />
  <TypeSignature Language="F#" Value="type UnprovisionApplicationTypeDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>使用して準備を解除するアプリケーションの種類について説明します<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.Fabric.Description.UnprovisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UnprovisionApplicationTypeDescription (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.UnprovisionApplicationTypeDescription.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationTypeName As String, applicationTypeVersion As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.UnprovisionApplicationTypeDescription : string * string -&gt; System.Fabric.Description.UnprovisionApplicationTypeDescription" Usage="new System.Fabric.Description.UnprovisionApplicationTypeDescription (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>アプリケーションの種類名のプロビジョニングを解除</para>
        </param>
        <param name="applicationTypeVersion">
          <para>アプリケーション タイプのバージョンのプロビジョニングを解除</para>
        </param>
        <summary>
          <para>インスタンスをインスタンス化<see cref="T:System.Fabric.Description.UnprovisionApplicationTypeDescription" />です。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>プロビジョニングを解除するアプリケーションの種類の名前を取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの種類名です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string" Usage="System.Fabric.Description.UnprovisionApplicationTypeDescription.ApplicationTypeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>プロビジョニングを解除アプリケーション タイプのバージョンを取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの種類のバージョン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Async">
      <MemberSignature Language="C#" Value="public bool Async { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Async" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.UnprovisionApplicationTypeDescription.Async" />
      <MemberSignature Language="VB.NET" Value="Public Property Async As Boolean" />
      <MemberSignature Language="F#" Value="member this.Async : bool with get, set" Usage="System.Fabric.Description.UnprovisionApplicationTypeDescription.Async" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定するかどうかを非同期的に発生する必要がありますプロビジョニング解除を示すフラグ。</para>
        </summary>
        <value>
          <para>かどうかは、このフラグが false の場合、動作は呼び出すことと同じ<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />です。 Timeout 引数は、サービスの提供解除操作自体に適用され、システムで、サービスの提供解除操作が完了した場合にのみ、返されるタスクが完了します。</para>
          <para>このフラグが true、timeout 引数は、メッセージの配信にだけ適用し、返されるタスクが 1 回が完了した場合、システムに要求が許可しました。 システムは、タイムアウトの制限がないサービスの提供解除操作を処理しを使用して、状態を照会できます<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>