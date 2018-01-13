<Type Name="TableConnectionPolicy" FullName="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy">
  <TypeSignature Language="C#" Value="public sealed class TableConnectionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TableConnectionPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TableConnectionPolicy" />
  <TypeSignature Language="F#" Value="type TableConnectionPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            関連付けられている接続ポリシーを表す<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />Azure CosmosDB テーブル サービスに接続します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableConnectionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.#ctor" />
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
            新しいインスタンスを初期化、 <see cref="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" /> Cosmos DB の Azure サービスに接続するクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableEndpointDiscovery">
      <MemberSignature Language="C#" Value="public bool EnableEndpointDiscovery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableEndpointDiscovery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableEndpointDiscovery As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableEndpointDiscovery : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの geo レプリケーションのデータベース アカウントのエンドポイントの探索を有効にするフラグを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティの値は true、SDK には、現在の書き込みは自動的に検出および要求を確認するために読み取り領域がで指定されている領域に基づく正しい地域に送信されるときに、<see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" />プロパティです。
            <value>既定値は true を示すエンドポイントの検出を有効にします。</value></remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConnectionLimit">
      <MemberSignature Language="C#" Value="public int MaxConnectionLimit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxConnectionLimit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxConnectionLimit" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConnectionLimit As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxConnectionLimit : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxConnectionLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの対象サービスのエンドポイントに対して許可される同時接続の最大数を設定します。
            </summary>
        <value>既定値は 50 です。</value>
        <remarks>
            この設定では、ゲートウェイのモードで適用のみです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryAttemptsOnThrottledRequests">
      <MemberSignature Language="C#" Value="public int MaxRetryAttemptsOnThrottledRequests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryAttemptsOnThrottledRequests As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryAttemptsOnThrottledRequests : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryAttemptsOnThrottledRequests" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Cosmos DB の Azure サービスには、クライアントに頻度の制限が適用されるので、要求が失敗した場合の再試行の最大数を設定します。
            </summary>
        <value>
            既定値は 9 です。 つまり、要求の率が制限されている場合に、同じ要求の送信は最大 10 倍の時間のサーバーにアプリケーションにエラーが返される前にします。 このプロパティの値が 0 に設定されている場合は行われません頻度のクライアントからの要求の制限で自動再試行および例外は、アプリケーション レベルで処理する必要があります。 
            </value>
        <remarks>
          <para>
            送信している場合、クライアント要求、許可されているレートよりも高速、サービスはクライアント使用率の上限を HttpStatusCode 429 (要求が多すぎます) を返します。 SDK の現在の実装は、時間、サービス、時間が経過後の処理を再試行するように指示し、待機します。  
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryWaitTimeInSeconds">
      <MemberSignature Language="C#" Value="public int MaxRetryWaitTimeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryWaitTimeInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryWaitTimeInSeconds : int with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.MaxRetryWaitTimeInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの秒単位の最大再試行時間を設定します。
            </summary>
        <value>
            既定値は 30 秒です。 
            </value>
        <remarks>
          <para>
            エラーを制限する速度のため、要求に失敗したときに、サービス応答を返信までの時間が経過する前にクライアントが再試行する必要がありますを示す値を含むです。 このプロパティは、すべての再試行回数の最大待機時間を設定するアプリケーションを使用します。
            累積待機時間が、これを超えると、値と、クライアントは再試行を停止、アプリケーションに、エラーが返されます。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreferredLocations">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;string&gt; PreferredLocations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;string&gt; PreferredLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreferredLocations As Collection(Of String)" />
      <MemberSignature Language="F#" Value="member this.PreferredLocations : System.Collections.ObjectModel.Collection&lt;string&gt;" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.PreferredLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得し、Azure Cosmos DB サービスの geo レプリケーションのデータベース アカウントの推奨される場所 (地域) を設定します。 たとえば、適切な場所として「東部米国」です。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            ときに<see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />が true であり、値のこのプロパティは空でない、SDK が、このプロパティの値が指定されていない場合それ以外の場合、操作を実行する指定された順序でコレクション内の場所を使用して、SDK と書き込みのリージョンを使用して、すべての操作の推奨される場所です。
            </para>
          <para>
            場合<see cref="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.EnableEndpointDiscovery" />が設定されているを false に、このプロパティの値は無視されます。 
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseDirectMode">
      <MemberSignature Language="C#" Value="public bool UseDirectMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseDirectMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseDirectMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UseDirectMode As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseDirectMode : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseDirectMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ダイレクト モードを使用して Azure Cosmos DB サービス flase への接続時に、テーブル REST API を使用して接続されます 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentSuffix">
      <MemberSignature Language="C#" Value="public string UserAgentSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UserAgentSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgentSuffix As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentSuffix : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UserAgentSuffix" />
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
            Azure Cosmos DB サービスの既定のユーザー エージェントに追加するサフィックスです。
            </summary>
        <value>To be added.</value>
        <remarks>
            すべての要求の送信後にこのプロパティの設定の効果はありません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTcpProtocol">
      <MemberSignature Language="C#" Value="public bool UseTcpProtocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseTcpProtocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseTcpProtocol" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTcpProtocol As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseTcpProtocol : bool with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy.UseTcpProtocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Cosmos DB の Azure サービスに接続するときは、TCP 接続プロトコルを使用します。
            </summary>
        <value>To be added.</value>
        <remarks>
            詳細については、次を参照してください。<see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#use-tcp">接続ポリシー: TCP プロトコルを使用して</see>です。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>