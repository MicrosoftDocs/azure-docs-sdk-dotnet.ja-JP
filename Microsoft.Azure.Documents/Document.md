<Type Name="Document" FullName="Microsoft.Azure.Documents.Document">
  <TypeSignature Language="C#" Value="public class Document : Microsoft.Azure.Documents.Resource, System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Document extends Microsoft.Azure.Documents.Resource implements class System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Document" />
  <TypeSignature Language="VB.NET" Value="Public Class Document&#xA;Inherits Resource&#xA;Implements IDynamicMetaObjectProvider" />
  <TypeSignature Language="F#" Value="type Document = class&#xA;    inherit Resource&#xA;    interface IDynamicMetaObjectProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Dynamic.IDynamicMetaObjectProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Cosmos DB の Azure サービスでドキュメントを表します。
            </summary>
    <remarks> 
            ドキュメントは、構造化された JSON ドキュメントです。 JSON ドキュメントのセットのスキーマがないと、ドキュメントは、カスタム プロパティの任意の数との添付ファイルのオプションのリストを含めることができます。 ドキュメントでは、アプリケーション リソースであるし、マスター _ キーまたはリソース キーを使用して承認することができます。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Document ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Document.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.Documents.Document" /> Azure Cosmos DB サービスのクラスです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AttachmentsLink">
      <MemberSignature Language="C#" Value="public string AttachmentsLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AttachmentsLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Document.AttachmentsLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AttachmentsLink As String" />
      <MemberSignature Language="F#" Value="member this.AttachmentsLink : string" Usage="Microsoft.Azure.Documents.Document.AttachmentsLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            自己リンクに対応するドキュメントの添付ファイル、Azure Cosmos DB サービスから取得します。
            </summary>
        <value>
            自己リンクに対応するドキュメントの添付ファイルです。
            </value>
        <remarks>
            0 になり、多くの添付ファイルの間のすべてのドキュメントが持つことができます。 添付ファイルのリンクには、ドキュメントに属している添付ファイルのフィードが含まれています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject">
      <MemberSignature Language="C#" Value="System.Dynamic.DynamicMetaObject IDynamicMetaObjectProvider.GetMetaObject (System.Linq.Expressions.Expression parameter);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Dynamic.DynamicMetaObject System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(class System.Linq.Expressions.Expression parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Document.System#Dynamic#IDynamicMetaObjectProvider#GetMetaObject(System.Linq.Expressions.Expression)" />
      <MemberSignature Language="VB.NET" Value="Function GetMetaObject (parameter As Expression) As DynamicMetaObject Implements IDynamicMetaObjectProvider.GetMetaObject" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(System.Linq.Expressions.Expression)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Dynamic.DynamicMetaObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.Linq.Expressions.Expression" />
      </Parameters>
      <Docs>
        <param name="parameter">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Document.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.Document.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore, PropertyName="ttl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービス内のドキュメントの秒単位で有効期限を設定します。
            </summary>
        <value>
            これは、省略可能なプロパティです。 有効な値はどちらかは 0 以外。 正の整数である必要があります '-1'、または<c>null</c>です。
            既定では、TimeToLive が意味を null に設定は、コレクションの継承し、<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />です。
            測定単位は秒です。 最大値は 2147483647 です。
            コレクションに関係なくは無期限にすること、値が-1 の場合は、<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />値。
            </value>
        <remarks>
          <para>
            コレクションを調べた後、ドキュメントの最終的な有効期間ポリシーの評価<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />です。
            </para>
          <para>
            ときに、<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />は<c>null</c>、ドキュメントは、コレクションを継承<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />です。
            場合、コレクションの<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />とその最終書き込み時刻以降、既定値に有効期限 (秒) の後に期限切れになるドキュメントを秒単位でそのに有効期限としてその値を継承し、0 以外の正の整数がします。 期限切れのドキュメントは、バック グラウンドで削除されます。
            それ以外の場合、ドキュメント無期限になります。
            </para>
          <para>
            ときに、 <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> '-1' で、コレクションに関係なく、ドキュメントが切れない<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />値。
            </para>
          <para>
            ときに、 <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" /> 0 以外の正の整数は、コレクションを確認する必要があります<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />です。
            場合、コレクションの<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />は<c>null</c>の有効期限はオフになっているコレクション、およびドキュメントの <see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />無視する必要があり、ドキュメントが決して期限切れです。
            それ以外の場合、ドキュメントの<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />が有効であります。 ドキュメントが期限切れになるに有効期限 (秒) の既定の後にその最終書き込み時刻以降 期限切れのドキュメントは、バック グラウンドで削除されます。
            </para>
          <para>
            次の表は、最終的な有効期間ポリシーを評価するコレクションの指定したマトリックスの例を示します<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />とドキュメントの<see cref="P:Microsoft.Azure.Documents.Document.TimeToLive" />します。
            </para>
          <list type="table">
            <listheader>
              <term>コレクション</term>
              <description>[マトリックス]</description>
            </listheader>
            <item>
              <term>DefaultTimeToLive = null</term>
              <description>
                <list type="table">
                  <listheader>
                    <term>ドキュメント</term>
                    <description>結果</description>
                  </listheader>
                  <item>
                    <term>TimeToLive = null</term>
                    <description>TTL は無効です。 ドキュメントには、(既定値) が決して期限切れです。</description>
                  </item>
                  <item>
                    <term>TimeToLive-1 を =</term>
                    <description>TTL は無効です。 ドキュメントが決して期限切れです。</description>
                  </item>
                  <item>
                    <term>TimeToLive = 2000</term>
                    <description>TTL は無効です。 ドキュメントが決して期限切れです。</description>
                  </item>
                </list>
              </description>
            </item>
            <item>
              <term>DefaultTimeToLive-1 を =</term>
              <description>
                <list type="table">
                  <listheader>
                    <term>ドキュメント</term>
                    <description>結果</description>
                  </listheader>
                  <item>
                    <term>TimeToLive = null</term>
                    <description>TTL は有効です。 ドキュメントには、(既定値) が決して期限切れです。</description>
                  </item>
                  <item>
                    <term>TimeToLive-1 を =</term>
                    <description>TTL は有効です。 ドキュメントが決して期限切れです。</description>
                  </item>
                  <item>
                    <term>TimeToLive = 2000</term>
                    <description>TTL は有効です。 ドキュメントは、2000 秒後に切れます。</description>
                  </item>
                </list>
              </description>
            </item>
            <item>
              <term>DefaultTimeToLive = 1000</term>
              <description>
                <list type="table">
                  <listheader>
                    <term>ドキュメント</term>
                    <description>結果</description>
                  </listheader>
                  <item>
                    <term>TimeToLive = null</term>
                    <description>TTL は有効です。 ドキュメントは、1000 秒 (既定) 後に切れます。</description>
                  </item>
                  <item>
                    <term>TimeToLive-1 を =</term>
                    <description>TTL は有効です。 ドキュメントが決して期限切れです。</description>
                  </item>
                  <item>
                    <term>TimeToLive = 2000</term>
                    <description>TTL は有効です。 ドキュメントは、2000 秒後に切れます。</description>
                  </item>
                </list>
              </description>
            </item>
          </list>
        </remarks>
        <altmember cref="T:Microsoft.Azure.Documents.DocumentCollection" />
        <example>
            次の例では、ドキュメントの内容から 'ttl' を削除します。
            ドキュメントは、コレクションの継承は<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />その有効期間の値として。
            <code language="c#"><![CDATA[
                document.TimeToLive = null;
            ]]></code></example>
        <example>
            以下の例では、ドキュメント必要がありますかに関係なく有効期限はありません。
            <code language="c#"><![CDATA[
                document.TimeToLive = -1;
            ]]></code></example>
        <example>
            次の例はの有効期限を設定、ドキュメントに対する秒単位でします。
            ドキュメント有効期限が切れる時刻以降、最後の書き込み 1000 秒後に、コレクションの<see cref="P:Microsoft.Azure.Documents.DocumentCollection.DefaultTimeToLive" />は<c>null</c>です。
            <code language="c#"><![CDATA[
            document.TimeToLive = 1000;
                ]]></code></example>
      </Docs>
    </Member>
  </Members>
</Type>