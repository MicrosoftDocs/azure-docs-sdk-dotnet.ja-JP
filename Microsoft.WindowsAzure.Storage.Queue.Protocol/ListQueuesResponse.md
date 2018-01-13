<Type Name="ListQueuesResponse" FullName="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse">
  <TypeSignature Language="C#" Value="public sealed class ListQueuesResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListQueuesResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListQueuesResponse&#xA;Inherits ResponseParsingBase(Of QueueEntry)" />
  <TypeSignature Language="F#" Value="type ListQueuesResponse = class&#xA;    inherit ResponseParsingBase&lt;QueueEntry&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            操作を一覧表示するキューからの応答を解析するためのメソッドを提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListQueuesResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse" Usage="new Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream">解析されるストリーム。</param>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListingContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext ListingContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext ListingContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.ListingContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListingContext As ListingContext" />
      <MemberSignature Language="F#" Value="member this.ListingContext : Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.ListingContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            XML 応答からリスト コンテキストを取得します。
            </summary>
        <value>一覧作成操作のパラメーターのセット。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public string Marker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Marker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Marker As String" />
      <MemberSignature Language="F#" Value="member this.Marker : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Marker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            XML 応答の一覧作成操作に指定されたマーカー値を取得します。
            </summary>
        <value>マーカー値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public int MaxResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResults As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            XML 応答の一覧作成操作に指定された MaxResults 値を取得します。
            </summary>
        <value>MaxResults の値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextMarker">
      <MemberSignature Language="C#" Value="public string NextMarker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextMarker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.NextMarker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextMarker As String" />
      <MemberSignature Language="F#" Value="member this.NextMarker : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.NextMarker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            一覧が完了しなかった場合は、XML 応答から NextMarker 値を取得します。
            </summary>
        <value>NextMarker 値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of QueueEntry)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;" Usage="listQueuesResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            操作を一覧表示するキューの応答に XML を解析します。
            </summary>
        <returns>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Prefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            XML 応答の一覧作成操作に指定されたプレフィックス値を取得します。
            </summary>
        <value>プレフィックスの値です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Queues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt; Queues { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt; Queues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Queues" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Queues As IEnumerable(Of QueueEntry)" />
      <MemberSignature Language="F#" Value="member this.Queues : seq&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.Protocol.ListQueuesResponse.Queues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            列挙可能なコレクションを取得<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry" />応答からのオブジェクト。
            </summary>
        <value>列挙可能なコレクション<see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueEntry" />オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>