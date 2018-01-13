<Type Name="ComputeNodeUser" FullName="Microsoft.Azure.Batch.ComputeNodeUser">
  <TypeSignature Language="C#" Value="public class ComputeNodeUser : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeUser extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ComputeNodeUser" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeUser&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type ComputeNodeUser = class&#xA;    interface ITransportObjectProvider&lt;ComputeNodeUser&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            特定の Azure Batch のコンピューティング ノードのユーザー。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics addOrUpdate = Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics.AddUser, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(valuetype Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics addOrUpdate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNodeUser.Commit(Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional addOrUpdate As ComputeNodeUserCommitSemantics = Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics.AddUser, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNodeUser.Commit (addOrUpdate, additionalBehaviors)" />
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
        <Parameter Name="addOrUpdate" Type="Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="addOrUpdate">実行するコミット操作の種類を選択します。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            作成または計算ノード上のユーザー アカウントを更新する呼び出しをブロックしています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics addOrUpdate = Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics.AddUser, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(valuetype Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics addOrUpdate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNodeUser.CommitAsync(Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNodeUser.CommitAsync (addOrUpdate, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addOrUpdate" Type="Microsoft.Azure.Batch.ComputeNodeUserCommitSemantics" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="addOrUpdate">実行するコミット操作の種類を選択します。</param>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            作成または計算ノード上のユーザー アカウントを更新する非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.CustomBehaviors" />
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
            取得または設定の動作を変更またはこれを介して行われる、Batch service への要求をカスタマイズするリスト<see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" />です。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>これらの動作は、子オブジェクトによって継承されます。</para>
          <para>変更は、コレクションの順序で適用されます。 最後には、wins を記述します。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNodeUser.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNodeUser.Delete additionalBehaviors" />
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
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <summary>
            コンピューティング ノードから現在のユーザーを削除する呼び出しです。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNodeUser.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNodeUser.DeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors">現在のオブジェクトに対して CustomBehaviors 後に適用される BatchClientBehavior インスタンスのコレクション。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            コンピューティング ノードから現在のユーザーを削除するための非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public DateTime ExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpiryTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiryTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.ExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、有効期限を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAdmin">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAdmin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAdmin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.IsAdmin" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAdmin As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAdmin : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.IsAdmin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー アカウントの管理者の特権レベルを設定します。 コミット操作のため UpdateUser が指定されている場合、このプロパティの値は無視されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            名前を取得または設定します。 コミット操作のため AddUser を指定すると、このプロパティの値が作成されるローカルの Windows アカウントの名前です。 コミット操作のため UpdateUser を指定すると、このプロパティの値は、ローカルの Windows アカウントの変更を選択します。 このプロパティを変更しても、コンピューティング ノード上のローカル Windows アカウントの名前は変更されません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            パスワードを取得または設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SshPublicKey">
      <MemberSignature Language="C#" Value="public string SshPublicKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshPublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeUser.SshPublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SshPublicKey As String" />
      <MemberSignature Language="F#" Value="member this.SshPublicKey : string with get, set" Usage="Microsoft.Azure.Batch.ComputeNodeUser.SshPublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンピューティング ノードにリモート ログインに使用できる SSH 公開キーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>公開キーが開いている SSH エンコーディングと互換性があるし、base 64 エンコードします。 このプロパティは、Linux ノードに対してのみ指定できます。 作成されたプールのこのプロパティが設定されている場合に、バッチ サービスがエラーを返します<see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />または<see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" />Windows のコンピューティング ノードです。</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>