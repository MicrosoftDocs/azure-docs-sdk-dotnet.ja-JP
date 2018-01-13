<Type Name="ServiceReplicaListener" FullName="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener">
  <TypeSignature Language="C#" Value="public sealed class ServiceReplicaListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceReplicaListener extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceReplicaListener" />
  <TypeSignature Language="F#" Value="type ServiceReplicaListener = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            通信リスナーとステートフル サービス レプリカのプロパティを表します。
            通信リスナーから与えられたエンドポイントは、通信リスナーの名前に関連付けられます。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceReplicaListener (Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; createCommunicationListener, string name = &quot;&quot;, bool listenOnSecondary = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class System.Fabric.StatefulServiceContext, class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; createCommunicationListener, string name, bool listenOnSecondary) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.#ctor(System.Func{System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener},System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createCommunicationListener As Func(Of StatefulServiceContext, ICommunicationListener), Optional name As String = &quot;&quot;, Optional listenOnSecondary As Boolean = false)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener : Func&lt;System.Fabric.StatefulServiceContext, Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; * string * bool -&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" Usage="new Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener (createCommunicationListener, name, listenOnSecondary)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createCommunicationListener" Type="System.Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="listenOnSecondary" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="createCommunicationListener">通信リスナーを作成するためのファクトリ メソッド</param>
        <param name="name">通信リスナーの名前です。 このパラメーターは省略可能なサービスに 1 つだけの通信リスナーです。</param>
        <param name="listenOnSecondary">通信リスナーがアクティブなセカンダリのレプリカがときに開く必要があるかどうかを指定します。 このパラメーターは省略可能</param>
        <summary>
            作成、ServiceReplicaListener
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCommunicationListener">
      <MemberSignature Language="C#" Value="public Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; CreateCommunicationListener { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class System.Fabric.StatefulServiceContext, class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; CreateCommunicationListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.CreateCommunicationListener" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreateCommunicationListener As Func(Of StatefulServiceContext, ICommunicationListener)" />
      <MemberSignature Language="F#" Value="member this.CreateCommunicationListener : Func&lt;System.Fabric.StatefulServiceContext, Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.CreateCommunicationListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>通信リスナーを作成するためのファクトリ メソッドを取得します。</para>
        </summary>
        <value>
          <para>通信リスナーを作成するためのファクトリ メソッド。</para>
        </value>
        <remarks>
          <para>ファクトリ メソッドがは、<see cref="T:System.Fabric.StatefulServiceContext" />と実装を返します。 通信リスナー<see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultName">
      <MemberSignature Language="C#" Value="public const string DefaultName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.DefaultName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultName : string" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.DefaultName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービス レプリカのリスナーの既定の名前。</para>
        </summary>
        <returns>
          <para>サービス レプリカのリスナーの既定の名前。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenOnSecondary">
      <MemberSignature Language="C#" Value="public bool ListenOnSecondary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ListenOnSecondary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.ListenOnSecondary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenOnSecondary As Boolean" />
      <MemberSignature Language="F#" Value="member this.ListenOnSecondary : bool" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.ListenOnSecondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>レプリカは、この通信リスナーを開く必要があるかどうかを示すフラグを取得、<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />です。</para>
          <para>このメンバーは、false はと、の通信リスナーが、レプリカが失われた場合にのみ開か<see cref="F:System.Fabric.ReplicaRole.Primary" />です。</para>
          <para>既定値は <languageKeyword>false</languageKeyword> です。</para>
        </summary>
        <value>
          <para>レプリカは、この通信リスナーを開く必要があるかどうかを示すフラグ<see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />です。</para>
        </value>
        <remarks>
          <para>このフラグ設定できますアプリケーションで許容されるデータの古い (ただし、一貫性のある) の読み取りと、プライマリ レプリカがビジー状態の読み取りを使用して効率的に書き込むときにし、セカンダリ レプリカからデータを読み取ることができます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>通信リスナーの名前を取得します。</para>
        </summary>
        <value>
          <para>通信リスナーの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>