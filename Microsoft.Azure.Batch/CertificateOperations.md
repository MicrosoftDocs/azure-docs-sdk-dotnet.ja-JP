<Type Name="CertificateOperations" FullName="Microsoft.Azure.Batch.CertificateOperations">
  <TypeSignature Language="C#" Value="public class CertificateOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type CertificateOperations = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Azure Batch アカウントの証明書関連の操作を実行します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelDeleteCertificate">
      <MemberSignature Language="C#" Value="public void CancelDeleteCertificate (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CancelDeleteCertificate(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificate(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CancelDeleteCertificate (thumbprintAlgorithm As String, thumbprint As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CancelDeleteCertificate : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificateOperations.CancelDeleteCertificate (thumbprintAlgorithm, thumbprint, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。 これには、sha1 があります。</param>
        <param name="thumbprint">削除に失敗した証明書の拇印です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />です。</param>
        <summary>
            指定された証明書の削除に失敗をキャンセルします。  これは、ため、証明書が、場合にのみ、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />状態、および復元する証明書、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" />状態です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
          <para>(アクティブなへの返送) ではなく証明書を削除する場合は、失敗した削除をキャンセルする必要はありません。 証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります (を参照してください<see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelDeleteCertificateAsync (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelDeleteCertificateAsync(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelDeleteCertificateAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificateOperations.CancelDeleteCertificateAsync (thumbprintAlgorithm, thumbprint, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;CancelDeleteCertificateAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。 これには、sha1 があります。</param>
        <param name="thumbprint">削除に失敗した証明書の拇印です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定された証明書の削除に失敗をキャンセルします。  これは、ため、証明書が、場合にのみ、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />状態、および復元する証明書、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" />状態です。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>
          <para>(アクティブなへの返送) ではなく証明書を削除する場合は、失敗した削除をキャンセルする必要はありません。 証明書がすべてのリソースで使用されていないと、し、再度試行できる証明書を削除することを確認する必要があります (を参照してください<see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
          <para>キャンセルは、非同期的に操作の実行を削除します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (byte[] cerRawData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(unsigned int8[] cerRawData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (cerRawData As Byte()) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : byte[] -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate cerRawData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cerRawData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="cerRawData">.Cer 形式で証明書データです。</param>
        <summary>
            新たに作成<see cref="T:Microsoft.Azure.Batch.Certificate" />.cer 形式のデータをメモリからです。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.Certificate" />バッチ サービスに追加されていない新しい証明書を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (string cerFileName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(string cerFileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (cerFileName As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate cerFileName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cerFileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cerFileName">.Cer ファイルへのパス。</param>
        <summary>
            新たに作成<see cref="T:Microsoft.Azure.Batch.Certificate" />.cer ファイルからです。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.Certificate" />バッチ サービスに追加されていない新しい証明書を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (byte[] pfxRawData, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(unsigned int8[] pfxRawData, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (pfxRawData As Byte(), password As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : byte[] * string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate (pfxRawData, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxRawData" Type="System.Byte[]" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxRawData">.Pfx 形式で証明書データです。</param>
        <param name="password">証明書の秘密キーにアクセスするパスワードです。</param>
        <summary>
            新たに作成<see cref="T:Microsoft.Azure.Batch.Certificate" />.pfx 形式のデータをメモリからです。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.Certificate" />バッチ サービスに追加されていない新しい証明書を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (string pfxFileName, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(string pfxFileName, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (pfxFileName As String, password As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : string * string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate (pfxFileName, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFileName" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxFileName">.Pfx ファイルへのパス。</param>
        <param name="password">証明書の秘密キーにアクセスするパスワードです。</param>
        <summary>
            新たに作成<see cref="T:Microsoft.Azure.Batch.Certificate" />.pfx ファイルからです。
            </summary>
        <returns>A<see cref="T:Microsoft.Azure.Batch.Certificate" />バッチ サービスに追加されていない新しい証明書を表すです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.CertificateOperations" />です。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これらの動作は、子オブジェクトによって継承されます。</para>
          <para>変更は、コレクションの順序で適用されます。 最後には、wins を記述します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificate">
      <MemberSignature Language="C#" Value="public void DeleteCertificate (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteCertificate(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificate(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteCertificate (thumbprintAlgorithm As String, thumbprint As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificate : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificateOperations.DeleteCertificate (thumbprintAlgorithm, thumbprint, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。 これには、sha1 があります。</param>
        <param name="thumbprint">削除する証明書の拇印です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />です。</param>
        <summary>
            Batch アカウントから証明書を削除します。
            </summary>
        <remarks>
          <para>削除操作は、証明書が削除されることを要求します。  要求に証明書を格納する、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" />状態です。
            バッチ サービスでは、その他のクライアント操作しなくても、実際の証明書の削除を実行します。</para>
          <para>リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。 証明書を削除することができます、前にする必要がありますのでことを確認します。</para>
          <list type="bullet">
            <item>
              <description>証明書は、すべてのプールに関連付けられていません。</description>
            </item>
            <item>
              <description>証明書は、すべてのコンピューティング ノードにインストールされていません。  (プールから証明書を削除した場合でもは削除されません、プール内の既存のコンピューティング ノードから再起動するまで。)</description>
            </item>
          </list>
          <para>使用されている証明書を削除しようとすると、削除は失敗します。 証明書の状態を変更する<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />です。
            使用することができます<see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />には、証明書の使用を続行することを決定する場合、アクティブに状態を設定します。</para>
          <para>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteCertificateAsync (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteCertificateAsync(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificateOperations.DeleteCertificateAsync (thumbprintAlgorithm, thumbprint, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;DeleteCertificateAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。 これには、sha1 があります。</param>
        <param name="thumbprint">削除する証明書の拇印です。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            Batch アカウントから証明書を削除します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" />。</returns>
        <remarks>
          <para>削除操作は、証明書が削除されることを要求します。  要求に証明書を格納する、<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" />状態です。
            バッチ サービスでは、その他のクライアント操作しなくても、実際の証明書の削除を実行します。</para>
          <para>リソース (プールまたはコンピューティング ノード) が使用されている場合、証明書を削除することはできません。 証明書を削除することができます、前にする必要がありますのでことを確認します。</para>
          <list type="bullet">
            <item>
              <description>証明書は、すべてのプールに関連付けられていません。</description>
            </item>
            <item>
              <description>証明書は、すべてのコンピューティング ノードにインストールされていません。  (プールから証明書を削除した場合でもは削除されません、プール内の既存のコンピューティング ノードから再起動するまで。)</description>
            </item>
          </list>
          <para>使用されている証明書を削除しようとすると、削除は失敗します。 証明書の状態を変更する<see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />です。
            使用することができます<see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />には、証明書の使用を続行することを決定する場合、アクティブに状態を設定します。</para>
          <para>削除操作は非同期的に実行されます。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate GetCertificate (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate GetCertificate(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificate(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetCertificate : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.GetCertificate (thumbprintAlgorithm, thumbprint, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。 これには、sha1 があります。</param>
        <param name="thumbprint">取得する証明書の拇印です。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            指定した <see cref="T:Microsoft.Azure.Batch.Certificate" /> を取得します。
            </summary>
        <returns>A <see cref="T:Microsoft.Azure.Batch.Certificate" /> Azure Batch アカウントに指定された証明書に関する情報を格納します。</returns>
        <remarks>これは、ブロッキング操作です。 非ブロッキング同等では、次を参照してください。<see cref="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificateAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt; GetCertificateAsync (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Certificate&gt; GetCertificateAsync(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificateAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetCertificateAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt;" Usage="certificateOperations.GetCertificateAsync (thumbprintAlgorithm, thumbprint, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;GetCertificateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">派生に使用するアルゴリズム、<paramref name="thumbprint" />パラメーター。 これには、sha1 があります。</param>
        <param name="thumbprint">取得する証明書の拇印です。</param>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            指定した <see cref="T:Microsoft.Azure.Batch.Certificate" /> を取得します。
            </summary>
        <returns>A <see cref="T:Microsoft.Azure.Batch.Certificate" /> Azure Batch アカウントに指定された証明書に関する情報を格納します。</returns>
        <remarks>証明書の取得操作は非同期的に実行されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt; ListCertificates (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.Certificate&gt; ListCertificates(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.ListCertificates(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListCertificates : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt;" Usage="certificateOperations.ListCertificates (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel">A<see cref="T:Microsoft.Azure.Batch.DetailLevel" />一覧をフィルター処理し、サービスから取得するプロパティを制御するために使用します。</param>
        <param name="additionalBehaviors">コレクション<see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" />後に、バッチ サービス要求に適用されているインスタンス、<see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />と<paramref name="detailLevel" />です。</param>
        <summary>
            列挙、<see cref="T:Microsoft.Azure.Batch.Certificate">証明書</see>Batch アカウントにします。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を非同期的または同期的に、証明書を列挙を使用できます。</returns>
        <remarks>このメソッドがすぐに戻る証明書は、コレクションが列挙される場合にのみ、バッチ サービスから取得されます。
            検索は非アトミックなです。証明書は、コレクションの列挙中にページで取得されます。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>