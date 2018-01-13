<Type Name="IProtectedItemOperationStatusesOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations">
  <TypeSignature Language="C#" Value="public interface IProtectedItemOperationStatusesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IProtectedItemOperationStatusesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IProtectedItemOperationStatusesOperations" />
  <TypeSignature Language="F#" Value="type IProtectedItemOperationStatusesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            ProtectedItemOperationStatusesOperations 操作です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, string fabricName, string containerName, string protectedItemName, string operationId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectedItemOperationStatusesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt;" Usage="iProtectedItemOperationStatusesOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, fabricName, containerName, protectedItemName, operationId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.OperationStatus&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="protectedItemName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            Recovery services コンテナーの名前。
            </param>
        <param name="resourceGroupName">
            リソース グループが、recovery services コンテナーの名前が存在します。
            </param>
        <param name="fabricName">
            バックアップ項目に関連付けられているファブリック名。
            </param>
        <param name="containerName">
            バックアップ アイテムに関連付けられたコンテナー名。
            </param>
        <param name="protectedItemName">
            バックアップ項目の名前詳細情報がフェッチされます。
            </param>
        <param name="operationId">
            OperationID では、状態をフェッチする必要があります、操作を表します。
            </param>
        <param name="customHeaders">
            追加されるヘッダーを要求します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            フェッチの状態のバックアップをトリガーするなどの操作、復元します。 進行中、完了または失敗の状態を指定できます。 操作のすべての可能な状態の OperationStatus 列挙体を参照することができます。 一部の操作は、ジョブを作成します。 このメソッドは、操作に関連付けられているジョブの一覧を返します。
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