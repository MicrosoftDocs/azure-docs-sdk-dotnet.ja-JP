<Type Name="CertificateOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificateOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificateOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificateOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificateOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate BeginCreate (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate BeginCreate(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreate(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreate (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <param name="parameters">
            証明書の作成に追加のパラメーターです。
            </param>
        <param name="ifMatch">
            更新する証明書のエンティティの状態 (ETag) のバージョン。 値"*"を証明書が既に存在する場合にのみ、操作を適用するために使用できます。 省略した場合、この操作常に使用されます。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しい証明書を作成するが、既存の証明書の更新を防ぐために使用できるようにします。 その他の値は無視されます。
            </param>
        <summary>
            指定されたアカウント内の新しい証明書を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; BeginCreateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; BeginCreateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;BeginCreateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <param name="parameters">
            証明書の作成に追加のパラメーターです。
            </param>
        <param name="ifMatch">
            更新する証明書のエンティティの状態 (ETag) のバージョン。 値"*"を証明書が既に存在する場合にのみ、操作を適用するために使用できます。 省略した場合、この操作常に使用されます。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しい証明書を作成するが、既存の証明書の更新を防ぐために使用できるようにします。 その他の値は無視されます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内の新しい証明書を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders BeginDelete (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders BeginDelete(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As CertificateDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDelete (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <summary>
            指定された証明書を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;BeginDeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletion">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate CancelDeletion (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate CancelDeletion(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletion(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CancelDeletion (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As Certificate" />
      <MemberSignature Language="F#" Value="static member CancelDeletion : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletion (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
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
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; CancelDeletionAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; CancelDeletionAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletionAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelDeletionAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CancelDeletionAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;CancelDeletionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
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
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Create (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Create(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Create(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null, Optional ifNoneMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Create (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <param name="parameters">
            証明書の作成に追加のパラメーターです。
            </param>
        <param name="ifMatch">
            更新する証明書のエンティティの状態 (ETag) のバージョン。 値"*"を証明書が既に存在する場合にのみ、操作を適用するために使用できます。 省略した場合、この操作常に使用されます。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しい証明書を作成するが、既存の証明書の更新を防ぐために使用できるようにします。 その他の値は無視されます。
            </param>
        <summary>
            指定されたアカウント内の新しい証明書を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; CreateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; CreateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <param name="parameters">
            証明書の作成に追加のパラメーターです。
            </param>
        <param name="ifMatch">
            更新する証明書のエンティティの状態 (ETag) のバージョン。 値"*"を証明書が既に存在する場合にのみ、操作を適用するために使用できます。 省略した場合、この操作常に使用されます。
            </param>
        <param name="ifNoneMatch">
            設定 ' *'、新しい証明書を作成するが、既存の証明書の更新を防ぐために使用できるようにします。 その他の値は無視されます。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたアカウント内の新しい証明書を作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders Delete (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders Delete(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Delete(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As CertificateDeleteHeaders" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Delete (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <summary>
            指定された証明書を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定された証明書を削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Get (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Get(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Get(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String) As Certificate" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Get (operations, resourceGroupName, accountName, certificateName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <summary>
            指定された証明書に関する情報を取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; GetAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; GetAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
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
    <Member MemberName="ListByBatchAccount">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccount (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccount(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccount(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccount (operations As ICertificateOperations, resourceGroupName As String, accountName As String, Optional maxresults As Nullable(Of Integer) = null, Optional select As String = null, Optional filter As String = null) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccount : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccount (operations, resourceGroupName, accountName, maxresults, select, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="maxresults">
            応答で返されるアイテムの最大数。
            </param>
        <param name="select">
            コンマ区切りのプロパティの一覧を返す必要があります。 例:"のプロパティ/provisioningState"です。 のみの上位レベル のプロパティのプロパティ/選択に対して有効です。
            </param>
        <param name="filter">
            OData フィルター式です。 フィルター処理の有効なプロパティは"のプロパティ/provisioningState"、"のプロパティ/provisioningStateTransitionTime"、"name"です。
            </param>
        <summary>
            すべての指定されたアカウントの証明書の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, Nullable&lt;int&gt; maxresults = null, string select = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, string select, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * Nullable&lt;int&gt; * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountAsync (operations, resourceGroupName, accountName, maxresults, select, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;ListByBatchAccountAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="maxresults">
            応答で返されるアイテムの最大数。
            </param>
        <param name="select">
            コンマ区切りのプロパティの一覧を返す必要があります。 例:"のプロパティ/provisioningState"です。 のみの上位レベル のプロパティのプロパティ/選択に対して有効です。
            </param>
        <param name="filter">
            OData フィルター式です。 フィルター処理の有効なプロパティは"のプロパティ/provisioningState"、"のプロパティ/provisioningStateTransitionTime"、"name"です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定されたアカウントの証明書の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccountNext (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; ListByBatchAccountNext(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNext(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBatchAccountNext (operations As ICertificateOperations, nextPageLink As String) As IPage(Of Certificate)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNext : Microsoft.Azure.Management.Batch.ICertificateOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <summary>
            すべての指定されたアカウントの証明書の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBatchAccountNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountNextAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt; ListByBatchAccountNextAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNextAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBatchAccountNextAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.ListByBatchAccountNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;ListByBatchAccountNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての指定されたアカウントの証明書の一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Batch.Models.Certificate Update (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Batch.Models.Certificate Update(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Update(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As ICertificateOperations, resourceGroupName As String, accountName As String, certificateName As String, parameters As CertificateCreateOrUpdateParameters, Optional ifMatch As String = null) As Certificate" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.Update (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <param name="parameters">
            証明書を更新するエンティティ。
            </param>
        <param name="ifMatch">
            更新する証明書のエンティティの状態 (ETag) のバージョン。 この値を省略するかに設定することができます"*"を無条件で操作を適用します。
            </param>
        <summary>
            既存の証明書のプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt; UpdateAsync (this Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Models.Certificate&gt; UpdateAsync(class Microsoft.Azure.Management.Batch.ICertificateOperations operations, string resourceGroupName, string accountName, string certificateName, class Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters parameters, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Batch.ICertificateOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Batch.ICertificateOperations * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;" Usage="Microsoft.Azure.Management.Batch.CertificateOperationsExtensions.UpdateAsync (operations, resourceGroupName, accountName, certificateName, parameters, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.CertificateOperationsExtensions/&lt;UpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.ICertificateOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Batch アカウントが含まれているリソース グループの名前。
            </param>
        <param name="accountName">
            Batch アカウントの名前。
            </param>
        <param name="certificateName">
            証明書の識別子。 これは、アルゴリズムとサムプリントをダッシュでつないで行う必要があり、要求の証明書データに一致する必要があります。 たとえば SHA1 a3d1c5 です。
            </param>
        <param name="parameters">
            証明書を更新するエンティティ。
            </param>
        <param name="ifMatch">
            更新する証明書のエンティティの状態 (ETag) のバージョン。 この値を省略するかに設定することができます"*"を無条件で操作を適用します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            既存の証明書のプロパティを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>