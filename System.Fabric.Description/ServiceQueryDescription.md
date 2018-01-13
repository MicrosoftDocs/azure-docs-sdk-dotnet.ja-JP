<Type Name="ServiceQueryDescription" FullName="System.Fabric.Description.ServiceQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceQueryDescription" />
  <TypeSignature Language="F#" Value="type ServiceQueryDescription = class" />
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
      <para>戻り値を調整するために指定できる複数のフィルターを表します。
            <see cref="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" /> で使用されます。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceQueryDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceQueryDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceQueryDescription : Uri -&gt; System.Fabric.Description.ServiceQueryDescription" Usage="new System.Fabric.Description.ServiceQueryDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">To be added.</param>
        <summary>
          <para><see cref="T:System.Fabric.Description.ServiceQueryDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ServiceQueryDescription.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>クエリを実行するサービスを含んでいるアプリケーションの URI 名を取得します。</para>
        </summary>
        <value>
          <para>クエリを実行するサービスを含んでいるアプリケーションの URI 名です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public string ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As String" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : string with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ContinuationToken" />
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
    <Member MemberName="ServiceNameFilter">
      <MemberSignature Language="C#" Value="public Uri ServiceNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ServiceNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceNameFilter : Uri with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ServiceNameFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはクエリを実行するサービスの URI 名を設定します。</para>
        </summary>
        <value>
          <para>クエリの実行にサービスの URI 名です。</para>
        </value>
        <remarks>
          <para>ServiceNameFilter と ServiceTypeNameFilter を同時に指定するはありません。</para>
          <para>ServiceNameFilter も ServiceTypeNameFilter のどちらも指定されていない場合は、指定したアプリケーションのすべてのサービスが返されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ServiceTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceQueryDescription.ServiceTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeNameFilter : string with get, set" Usage="System.Fabric.Description.ServiceQueryDescription.ServiceTypeNameFilter" />
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
          <para>取得またはクエリを実行するサービスをフィルター処理するために使用するサービスの種類名を設定します。
            このサービスの種類は、サービスが返されます。</para>
        </summary>
        <value>
          <para>クエリを実行するサービスをフィルター処理するために使用されるサービスの種類名。</para>
        </value>
        <remarks>
          <para>ServiceNameFilter と ServiceTypeNameFilter を同時に指定するはありません。</para>
          <para>ServiceNameFilter も ServiceTypeNameFilter のどちらも指定されていない場合は、指定したアプリケーションのすべてのサービスが返されます。</para>
          <para>このフィルターは、大文字小文字を区別します。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>