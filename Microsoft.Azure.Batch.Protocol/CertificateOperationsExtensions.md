<Type Name="CertificateOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificateOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificateOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificateOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificateOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            CertificateOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders Add (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders Add(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter * Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Add (operations, certificate, certificateAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificate" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
        <Parameter Name="certificateAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="certificate">
            追加する証明書。
            </param>
        <param name="certificateAddOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアカウントに証明書を追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter * Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.AddAsync (operations, certificate, certificateAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificate" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
        <Parameter Name="certificateAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="certificate">
            追加する証明書。
            </param>
        <param name="certificateAddOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウントに証明書を追加します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletion">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders CancelDeletion (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders CancelDeletion(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletion(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions)" />
      <MemberSignature Language="F#" Value="static member CancelDeletion : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletion (operations, thumbprintAlgorithm, thumbprint, certificateCancelDeletionOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateCancelDeletionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="thumbprintAlgorithm">
            サムプリントのパラメーターを派生させるために使用されるアルゴリズム。 これには、sha1 があります。
            </param>
        <param name="thumbprint">
            削除されている証明書の拇印です。
            </param>
        <param name="certificateCancelDeletionOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアカウントからの証明書の削除に失敗をキャンセルします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プールで使用されている証明書を削除またはコンピューティング ノードしようとすると、証明書の状態は deleteFailed に変更します。 証明書の使用を続行することを決定する場合をアクティブに証明書の状態を設定します。 この操作を使用できます。 証明書を削除する場合は、削除が失敗した後、この操作を実行する必要はありません。 証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt; CancelDeletionAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt; CancelDeletionAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletionAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelDeletionAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletionAsync (operations, thumbprintAlgorithm, thumbprint, certificateCancelDeletionOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;CancelDeletionAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateCancelDeletionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="thumbprintAlgorithm">
            サムプリントのパラメーターを派生させるために使用されるアルゴリズム。 これには、sha1 があります。
            </param>
        <param name="thumbprint">
            削除されている証明書の拇印です。
            </param>
        <param name="certificateCancelDeletionOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウントからの証明書の削除に失敗をキャンセルします。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            プールで使用されている証明書を削除またはコンピューティング ノードしようとすると、証明書の状態は deleteFailed に変更します。 証明書の使用を続行することを決定する場合をアクティブに証明書の状態を設定します。 この操作を使用できます。 証明書を削除する場合は、削除が失敗した後、この操作を実行する必要はありません。 証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Delete (operations, thumbprintAlgorithm, thumbprint, certificateDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="thumbprintAlgorithm">
            サムプリントのパラメーターを派生させるために使用されるアルゴリズム。 これには、sha1 があります。
            </param>
        <param name="thumbprint">
            削除する証明書の拇印です。
            </param>
        <param name="certificateDeleteOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定されたアカウントから証明書を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。 証明書を削除することができます、前にする必要がありますので、証明書に関連付けられていない既存のプールのコンピューティング ノードであっても、プールから証明書を削除する場合は削除されません、プール内の既存のコンピューティング ノードから再起動するまで)、証明書がインストールされていないことを確認して、証明書の実行中のタスクが依存していません。 使用されている証明書を削除しようとすると、削除は失敗します。 証明書の状態は、deleteFailed に変更します。 取り消す証明書の削除を使用して、証明書の使用を続行することを決定する場合にアクティブな状態を設定することができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.DeleteAsync (operations, thumbprintAlgorithm, thumbprint, certificateDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="thumbprintAlgorithm">
            サムプリントのパラメーターを派生させるために使用されるアルゴリズム。 これには、sha1 があります。
            </param>
        <param name="thumbprint">
            削除する証明書の拇印です。
            </param>
        <param name="certificateDeleteOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウントから証明書を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>
            リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。 証明書を削除することができます、前にする必要がありますので、証明書に関連付けられていない既存のプールのコンピューティング ノードであっても、プールから証明書を削除する場合は削除されません、プール内の既存のコンピューティング ノードから再起動するまで)、証明書がインストールされていないことを確認して、証明書の実行中のタスクが依存していません。 使用されている証明書を削除しようとすると、削除は失敗します。 証明書の状態は、deleteFailed に変更します。 取り消す証明書の削除を使用して、証明書の使用を続行することを決定する場合にアクティブな状態を設定することができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.Certificate Get (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.Certificate Get(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.Certificate" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Get (operations, thumbprintAlgorithm, thumbprint, certificateGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="thumbprintAlgorithm">
            サムプリントのパラメーターを派生させるために使用されるアルゴリズム。 これには、sha1 があります。
            </param>
        <param name="thumbprint">
            取得する証明書の拇印です。
            </param>
        <param name="certificateGetOptions">
            操作の追加パラメーター
            </param>
        <summary>
            指定された証明書に関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.GetAsync (operations, thumbprintAlgorithm, thumbprint, certificateGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="thumbprintAlgorithm">
            サムプリントのパラメーターを派生させるために使用されるアルゴリズム。 これには、sha1 があります。
            </param>
        <param name="thumbprint">
            取得する証明書の拇印です。
            </param>
        <param name="certificateGetOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書に関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; List (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; List(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.List (operations, certificateListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificateListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="certificateListOptions">
            操作の追加パラメーター
            </param>
        <summary>
            すべての指定したアカウントに追加されている証明書の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListAsync (operations, certificateListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificateListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="certificateListOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定したアカウントに追加されている証明書の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; ListNext (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; ListNext(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNext (operations, nextPageLink, certificateListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="certificateListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="certificateListNextOptions">
            操作の追加パラメーター
            </param>
        <summary>
            すべての指定したアカウントに追加されている証明書の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNextAsync (operations, nextPageLink, certificateListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="certificateListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="certificateListNextOptions">
            操作の追加パラメーター
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定したアカウントに追加されている証明書の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>