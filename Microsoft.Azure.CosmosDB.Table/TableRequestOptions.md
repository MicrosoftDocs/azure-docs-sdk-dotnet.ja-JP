<Type Name="TableRequestOptions" FullName="Microsoft.Azure.CosmosDB.Table.TableRequestOptions">
  <TypeSignature Language="C#" Value="public sealed class TableRequestOptions : Microsoft.Azure.Storage.IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableRequestOptions extends System.Object implements class Microsoft.Azure.Storage.IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableRequestOptions&#xA;Implements IRequestOptions" />
  <TypeSignature Language="F#" Value="type TableRequestOptions = class&#xA;    interface IRequestOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Storage.IRequestOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            テーブル サービスに対する要求で指定できるタイムアウトと再試行のポリシーのオプションのセットを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableRequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableRequestOptions (Microsoft.Azure.CosmosDB.Table.TableRequestOptions other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.#ctor(Microsoft.Azure.CosmosDB.Table.TableRequestOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (other As TableRequestOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableRequestOptions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions -&gt; Microsoft.Azure.CosmosDB.Table.TableRequestOptions" Usage="new Microsoft.Azure.CosmosDB.Table.TableRequestOptions other" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
      </Parameters>
      <Docs>
        <param name="other"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />の新しいインスタンスを初期化するために使用されるオブジェクト、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />クラスです。</param>
        <summary>
            <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> を指定して、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy EncryptionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy EncryptionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionPolicy As TableEncryptionPolicy" />
      <MemberSignature Language="F#" Value="member this.EncryptionPolicy : Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableEncryptionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求の暗号化ポリシーを設定します。
            </summary>
        <value><see cref="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionPolicy" /> 型のオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionResolver">
      <MemberSignature Language="C#" Value="public Func&lt;string,string,string,bool&gt; EncryptionResolver { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`4&lt;string, string, string, bool&gt; EncryptionResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionResolver" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionResolver As Func(Of String, String, String, Boolean)" />
      <MemberSignature Language="F#" Value="member this.EncryptionResolver : Func&lt;string, string, string, bool&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.EncryptionResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.String,System.String,System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を示すかどうかは、プロパティを暗号化するか、パーティション キー、行キー、およびプロパティ名を指定する値を取得するデリゲート。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.LocationMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.LocationMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Storage.RetryPolicies.LocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求の配置モードを設定します。
            </summary>
        <value>A<see cref="T:Microsoft.Azure.Storage.RetryPolicies.LocationMode" />要求の配置モードを示す列挙値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.MaximumExecutionTime" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.MaximumExecutionTime</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求に対応するすべての潜在的な再試行の最大実行時間を設定します。
            </summary>
        <value>A<see cref="T:System.TimeSpan" />要求の再試行の最大実行時間を表すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PayloadFormat">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt; PayloadFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt; PayloadFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PayloadFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property PayloadFormat As Nullable(Of TablePayloadFormat)" />
      <MemberSignature Language="F#" Value="member this.PayloadFormat : Nullable&lt;Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PayloadFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.CosmosDB.Table.TablePayloadFormat&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePayloadFormat" />要求に対して使用されます。
            </summary>
        <value><see cref="T:Microsoft.Azure.CosmosDB.Table.TablePayloadFormat" /> 列挙値。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProjectSystemProperties">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ProjectSystemProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ProjectSystemProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ProjectSystemProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property ProjectSystemProperties As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ProjectSystemProperties : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ProjectSystemProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクエリにパーティション キーと行キーなどのシステム プロパティを含めるオプションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyResolver">
      <MemberSignature Language="C#" Value="public Func&lt;string,string,string,string,Microsoft.Azure.CosmosDB.Table.EdmType&gt; PropertyResolver { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`5&lt;string, string, string, string, valuetype Microsoft.Azure.CosmosDB.Table.EdmType&gt; PropertyResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PropertyResolver" />
      <MemberSignature Language="VB.NET" Value="Public Property PropertyResolver As Func(Of String, String, String, String, EdmType)" />
      <MemberSignature Language="F#" Value="member this.PropertyResolver : Func&lt;string, string, string, string, Microsoft.Azure.CosmosDB.Table.EdmType&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.PropertyResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.String,System.String,System.String,System.String,Microsoft.Azure.CosmosDB.Table.EdmType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を取得するために使用するデリゲート、<see cref="T:Microsoft.Azure.CosmosDB.Table.EdmType" />エンティティのプロパティに、パーティション キー、行キー、およびプロパティ名を指定します。 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RequireEncryption" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.RequireEncryption</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクライアント ライブラリによって読み取りし、書き込みのデータを暗号化するかどうかを示す値を設定します。
            </summary>
        <value>使用して<c>true</c>すべてのトランザクションの暗号化/暗号化解除、それ以外のデータがする必要がありますを指定する<c>false</c>です。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.RetryPolicy" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.RetryPolicy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または要求の再試行ポリシーを設定します。
            </summary>
        <value><see cref="T:Microsoft.Azure.Storage.RetryPolicies.IRetryPolicy" /> 型のオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.ServerTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Storage.IRequestOptions.ServerTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、サーバーに要求のタイムアウト間隔を設定します。
            </summary>
        <value>A<see cref="T:System.TimeSpan" />の要求に対するサーバー タイムアウト間隔を表すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionToken">
      <MemberSignature Language="C#" Value="public string SessionToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableRequestOptions.SessionToken" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionToken As String" />
      <MemberSignature Language="F#" Value="member this.SessionToken : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableRequestOptions.SessionToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービス内のセッションの整合性に使用するためのトークンを設定します。
            </summary>
        <value>
            セッションで使用するためのトークンです。
            </value>
        <remarks>
            1 つ、 <see cref="T:Microsoft.Azure.CosmosDB.ConsistencyLevel" /> Azure Cosmos DB は、セッションのです。  
            <para>セッションの整合性を使用するときに、Azure Cosmos DB への新しい各書き込み要求には新しい SessionToken が割り当てられます。
            <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />はこのトークンを使用して内部的に読み取り/クエリ要求ごとに整合性レベルの設定が維持されるようにします。
            
             <para>一部のシナリオでは、考えてください。 このセッションを管理する必要があります。たとえば web アプリケーションは、複数のノード、各ノードが、それぞれのインスタンスの<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />場合に、同じセッションに参加するこれらのノード (できるように、独自の書き込み一貫して全体で読み取る web 層)、SessionToken を送信する必要がありますクライアント層のノードを 1 つの書き込みアクションのいずれかで、cookie、またはその他の機構を使用していて、web 層にそのトークンのフローの後続の読み取り。
            これは、Azure ロード バランサーなどの要求間でセッション アフィニティが維持されないラウンド ロビンのロード バランサーを使用している場合  
            読み取りでした可能性があります。 そこで別のノードで、書き込み要求をセッションが作成されました。 
            </para><para>前述のように、Azure Cosmos DB SessionToken 間をフローしない場合を終了して、読み取りの一貫性のない結果を時間の期間。</para></para></remarks>
        <altmember cref="T:Microsoft.Azure.CosmosDB.ConsistencyLevel" />
      </Docs>
    </Member>
  </Members>
</Type>