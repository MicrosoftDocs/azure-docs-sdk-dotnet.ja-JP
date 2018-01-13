<Type Name="RetryOptions" FullName="Microsoft.Azure.Documents.Client.RetryOptions">
  <TypeSignature Language="C#" Value="public class RetryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RetryOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.RetryOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class RetryOptions" />
  <TypeSignature Language="F#" Value="type RetryOptions = class" />
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
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            RetryOptions クラスは、アプリケーションが Azure Cosmos DB サービスの組み込みの再試行ポリシーをカスタマイズする設定できるパラメーターを定義します。
            </summary>
    <remarks>
            <see cref="T:Microsoft.Azure.Documents.Client.DocumentClient" />クラスは、特定の種類の例外の再試行をサポートしています。 このクラスは、アプリケーションの再試行動作を制御するためのオプションを提供します。
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.RetryOptions.#ctor" />
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
            RetryOptions クラスの新しいインスタンスを作成して Azure Cosmos DB サービスの既定値にすべてのプロパティを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryAttemptsOnThrottledRequests">
      <MemberSignature Language="C#" Value="public int MaxRetryAttemptsOnThrottledRequests { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryAttemptsOnThrottledRequests" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryAttemptsOnThrottledRequests As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryAttemptsOnThrottledRequests : int with get, set" Usage="Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryAttemptsOnThrottledRequests" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Cosmos DB の Azure サービスには、クライアントに頻度の制限が適用されるので、要求が失敗した場合の再試行の最大数を設定します。
            </summary>
        <value>
            既定値は 9 です。 つまり、要求の率が制限されている場合に、同じ要求の送信は最大 10 倍の時間のサーバーにアプリケーションにエラーが返される前にします。 このプロパティの値が 0 に設定されている場合は行われません頻度のクライアントからの要求の制限で自動再試行および例外は、アプリケーション レベルで処理する必要があります。 この値を設定する方法の例を参照してください<see cref="P:Microsoft.Azure.Documents.Client.ConnectionPolicy.RetryOptions" />です。
            </value>
        <remarks>
          <para>
            送信している場合、クライアント要求、許可されているレートよりも高速、サービスはクライアント使用率の上限を HttpStatusCode 429 (要求が多すぎます) を返します。 SDK の現在の実装は、時間、サービス、時間が経過後の処理を再試行するように指示し、待機します。  
            </para>
          <para>
            詳細については、次を参照してください。<see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#429">ハンドル レート制限/要求の処理率が大きすぎます</see>です。
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryWaitTimeInSeconds">
      <MemberSignature Language="C#" Value="public int MaxRetryWaitTimeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryWaitTimeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryWaitTimeInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryWaitTimeInSeconds : int with get, set" Usage="Microsoft.Azure.Documents.Client.RetryOptions.MaxRetryWaitTimeInSeconds" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Azure Cosmos DB サービスの秒単位の最大再試行時間を設定します。
            </summary>
        <value>
            既定値は 30 秒です。 この値を設定する方法の例を参照してください<see cref="P:Microsoft.Azure.Documents.Client.ConnectionPolicy.RetryOptions" />です。
            </value>
        <remarks>
          <para>
            エラーを制限する速度のため、要求に失敗したときに、サービス応答を返信する前に、クライアントが再試行する必要がありますかを示す値を含む、<see cref="P:Microsoft.Azure.Documents.DocumentClientException.RetryAfter" />期間が経過しました。 このプロパティは、すべての再試行回数の最大待機時間を設定するアプリケーションを使用します。
            累積待機時間が、これを超えると、値と、クライアントは再試行を停止、アプリケーションに、エラーが返されます。
            </para>
          <para>
            詳細については、次を参照してください。<see href="https://docs.microsoft.com/en-us/azure/documentdb/documentdb-performance-tips#429">ハンドル レート制限/要求の処理率が大きすぎます</see>です。
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>