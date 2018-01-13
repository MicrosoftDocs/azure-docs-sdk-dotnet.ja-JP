<Type Name="ServiceGroupMemberDescription" FullName="System.Fabric.Description.ServiceGroupMemberDescription">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupMemberDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupMemberDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceGroupMemberDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupMemberDescription" />
  <TypeSignature Language="F#" Value="type ServiceGroupMemberDescription = class" />
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
      <para>サービス グループに属しているサービスをについて説明します。  </para>
    </summary>
    <remarks>
      <para>A<see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />通常ステートレスまたはステートフルなサービスの説明のサブセットが含まれています。 これらのフィールドは、グループ内にサービスに関連します。 については、パーティション分割などの通常のサービスの説明に存在するその他のフィールドを使用して、サービスのグループのプロパティになります、<see cref="T:System.Fabric.Description.ServiceGroupDescription" />です。</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupMemberDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupMemberDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>空の <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> オブジェクトを作成します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupMemberDescription (string serviceTypeName, Uri serviceName, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceTypeName, class System.Uri serviceName, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceGroupMemberDescription.#ctor(System.String,System.Uri,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serviceTypeName As String, serviceName As Uri, initializationData As Byte())" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceGroupMemberDescription : string * Uri * byte[] -&gt; System.Fabric.Description.ServiceGroupMemberDescription" Usage="new System.Fabric.Description.ServiceGroupMemberDescription (serviceTypeName, serviceName, initializationData)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para>サービス グループ メンバーのサービスの種類名です。</para>
        </param>
        <param name="serviceName">
          <para>メンバーのセットに完全修飾名。 たとえば、グループ名がファブリック:/G1 とメンバーは、M1、しを指定する完全な名前がファブリック:/G&amp;#1;M1 です。</para>
        </param>
        <param name="initializationData">
          <para>メンバーのファクトリを初期化データとして提供される byte[] です。</para>
        </param>
        <summary>
          <para>作成、<see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />オブジェクトは、指定されたパラメーターで初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupMemberDescription.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[] with get, set" Usage="System.Fabric.Description.ServiceGroupMemberDescription.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Performance", "CA1819:PropertiesShouldNotReturnArrays", Justification="Manipulation of byte[] does not have any effect on the ServiceDescription already registered")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはこのサービス グループのメンバーの初期化データを設定します。</para>
        </summary>
        <value>
          <para>このサービス グループ メンバーの初期化データ。</para>
        </value>
        <remarks>
          <para>この情報はサービス グループ ファクトリの初期化データとして作成されるときに、オブジェクトに対応するサービス ファクトリに渡し、このサービス グループ メンバーの初期化データを渡す方法と通常ステートレスのようなのインスタンスまたはステートフルなサービス インスタンスが作成されます。</para>
        </remarks>
        <altmember cref="M:System.Fabric.IStatelessServiceFactory.CreateInstance(System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
        <altmember cref="M:System.Fabric.IStatefulServiceFactory.CreateReplica(System.String,System.Uri,System.Byte[],System.Guid,System.Int64)" />
        <altmember cref="P:System.Fabric.Description.ServiceDescription.InitializationData" />
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.ServiceLoadMetricDescription&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupMemberDescription.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metrics As IList(Of ServiceLoadMetricDescription)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceLoadMetricDescription&gt;" Usage="System.Fabric.Description.ServiceGroupMemberDescription.Metrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.ServiceLoadMetricDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定のコレクション<see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />このサービスのオブジェクト。 メトリックの収集が含まれています、<see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />このサービスに関連するオブジェクト。</para>
        </summary>
        <value>
          <para>返します<see cref="T:System.Collections.Generic.IList`1" />型の<see cref="T:System.Fabric.Description.ServiceLoadMetricDescription" />します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupMemberDescription.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri with get, set" Usage="System.Fabric.Description.ServiceGroupMemberDescription.ServiceName" />
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
          <para>取得またはサービス グループ内のサービスの名前を設定します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Uri" />サービス名を表すです。</para>
        </value>
        <remarks>
          <para>サービスは独立して、サービス グループの内側という名前です。 この名前は、サービスを解決するのには、安定したファブリック名の一部として使用されます。 たとえば、サービス グループの名前が"fabric:/グループ a"サービス名は、ここでは、"svc1"し、クライアントは、名前を解決する必要がありますを指定して"ファブリック:/グループ a #svc1"このサービスを解決するのには。</para>
        </remarks>
        <altmember cref="T:System.Fabric.Description.ServiceDescription" />
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceGroupMemberDescription.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string with get, set" Usage="System.Fabric.Description.ServiceGroupMemberDescription.ServiceTypeName" />
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
          <para>取得またはこのサービス グループ メンバーのサービスの種類を設定します。</para>
        </summary>
        <value>
          <para>サービス型の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>