<Type Name="ITransformationsOperations" FullName="Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations">
  <TypeSignature Language="C#" Value="public interface ITransformationsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITransformationsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITransformationsOperations" />
  <TypeSignature Language="F#" Value="type ITransformationsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            TransformationsOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrReplaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, string ifNoneMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, class Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt; CreateOrReplaceWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, string ifNoneMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations.CreateOrReplaceWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrReplaceWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt;" Usage="iTransformationsOperations.CreateOrReplaceWithHttpMessagesAsync (transformation, resourceGroupName, jobName, transformationName, ifMatch, ifNoneMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsCreateOrReplaceHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="transformation">
            新しい変換を作成するか、ストリーミング ジョブの下にある既存のものを置き換えるに使用される変換の定義。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="transformationName">
            変換の名前です。
            </param>
        <param name="ifMatch">
            変換の ETag です。 常に現在の変換を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しい変換を作成するが、既存の変換の更新を防ぐために使用できるようにします。 その他の値は、412 の前提条件が失敗の応答になります。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            変換を作成するか、既存のストリーミング ジョブの下で、既存の変換を置き換えます。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
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
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string jobName, string transformationName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, class Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string jobName, string transformationName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt;" Usage="iTransformationsOperations.GetWithHttpMessagesAsync (resourceGroupName, jobName, transformationName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="transformationName">
            変換の名前です。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定した変換の詳細を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
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
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync (Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, class Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt; UpdateWithHttpMessagesAsync(class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, string resourceGroupName, string jobName, string transformationName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.ITransformationsOperations.UpdateWithHttpMessagesAsync(Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation, Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt;" Usage="iTransformationsOperations.UpdateWithHttpMessagesAsync (transformation, resourceGroupName, jobName, transformationName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,Microsoft.Azure.Management.StreamAnalytics.Models.TransformationsUpdateHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="transformationName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="transformation">
            変換オブジェクトです。 既存の変換 (ie 対応するプロパティをここで指定したプロパティが上書きされます。そのプロパティが更新されます)。 ここでは null に設定されている任意のプロパティがありことを意味既存の変換では、対応するプロパティは同じままこの PATCH 操作の結果として変更されません。
            </param>
        <param name="resourceGroupName">
            リソースを格納するリソース グループの名前。 この値は、Azure リソース マネージャー API またはポータルから取得できます。
            </param>
        <param name="jobName">
            ストリーミング ジョブの名前。
            </param>
        <param name="transformationName">
            変換の名前です。
            </param>
        <param name="ifMatch">
            変換の ETag です。 常に現在の変換を上書きするには、この値を省略します。 誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存のストリーミング ジョブの下にある既存の変換を更新します。
            これは、(ie 部分的に更新を使用できます。 1 つまたは 2 つのプロパティの更新)、残りのジョブまたは変換の定義に影響を与えずに変換します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
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