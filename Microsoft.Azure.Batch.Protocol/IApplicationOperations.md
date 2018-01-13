<Type Name="IApplicationOperations" FullName="Microsoft.Azure.Batch.Protocol.IApplicationOperations">
  <TypeSignature Language="C#" Value="public interface IApplicationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IApplicationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationOperations" />
  <TypeSignature Language="F#" Value="type IApplicationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ApplicationOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string applicationId, Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary, class Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string applicationId, class Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions applicationGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IApplicationOperations.GetWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary, Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt;" Usage="iApplicationOperations.GetWithHttpMessagesAsync (applicationId, applicationGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary,Microsoft.Azure.Batch.Protocol.Models.ApplicationGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="applicationGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationId">
            アプリケーションの ID。
            </param>
        <param name="applicationGetOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアプリケーションに関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。 管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;,Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions applicationListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IApplicationOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;, Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt;" Usage="iApplicationOperations.ListNextWithHttpMessagesAsync (nextPageLink, applicationListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;,Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="applicationListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="applicationListNextOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定したアカウントで利用できるアプリケーションの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。 管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;,Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;, class Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions applicationListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IApplicationOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;, Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt;" Usage="iApplicationOperations.ListWithHttpMessagesAsync (applicationListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationSummary&gt;,Microsoft.Azure.Batch.Protocol.Models.ApplicationListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ApplicationListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationListOptions">
            操作の追加パラメーター
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定したアカウントで利用できるアプリケーションの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            この操作は、アプリケーションとコンピューティング ノードで使用可能なバージョンのみを返します。つまり、アプリケーション パッケージの参照で使用できます。 管理者についてアプリケーションとはまだ計算ノードに使用できるバージョンは、Azure ポータルまたは Azure リソース マネージャー API を使用します。
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            操作には、無効な状態コードが返された場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            応答をシリアル化を解除できない場合にスローされます。
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            必須のパラメーターが null の場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>