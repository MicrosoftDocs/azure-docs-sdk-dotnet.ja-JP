<Type Name="ExternalChildResource&lt;FluentModelT,InnerModelT,IParentT,ParentImplT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;FluentModelT,InnerModelT,IParentT,ParentImplT&gt;">
  <TypeSignature Language="C#" Value="public abstract class ExternalChildResource&lt;FluentModelT,InnerModelT,IParentT,ParentImplT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;InnerModelT,ParentImplT,IParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;FluentModelT&gt; where FluentModelT : class, IExternalChildResource&lt;FluentModelT,IParentT&gt; where ParentImplT : IParentT" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ExternalChildResource`4&lt;class (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;!FluentModelT, !IParentT&gt;) FluentModelT, InnerModelT, IParentT, (!IParentT) ParentImplT&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource`3&lt;!InnerModelT, !ParentImplT, !IParentT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;!FluentModelT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ExternalChildResource(Of FluentModelT, InnerModelT, IParentT, ParentImplT)&#xA;Inherits ChildResource(Of InnerModelT, ParentImplT, IParentT)&#xA;Implements IRefreshable(Of FluentModelT)" />
  <TypeSignature Language="F#" Value="type ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt; = class&#xA;    inherit ChildResource&lt;'InnerModelT, #'IParentT, 'IParentT&gt;&#xA;    interface IRefreshable&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentModelT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;FluentModelT,IParentT&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="InnerModelT" />
    <TypeParameter Name="IParentT" />
    <TypeParameter Name="ParentImplT">
      <Constraints>
        <BaseTypeName>IParentT</BaseTypeName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;InnerModelT,ParentImplT,IParentT&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="InnerT">InnerModelT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="ParentImplT">ParentImplT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="IParentT">IParentT</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;FluentModelT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="FluentModelT">外部の子リソース fluent インターフェイス</typeparam>
    <typeparam name="InnerModelT">Azure の内部リソース クラス型の子リソースを表す</typeparam>
    <typeparam name="IParentT">親 fluent インターフェイス</typeparam>
    <typeparam name="ParentImplT">親リソースの実装の種類</typeparam>
    <summary>
            子の外部化されたリソースの抽象実装。
            次の条件を満たす必要のある外部の子リソースの対象となる: するには
            1. これは、親リソースに関連付けられては常にあり、親の親、子のリソースを削除する場合などが自動的に削除することがなく存在がありません。
            2. 親は、子リソースのコレクション (つまりとしてインライン コレクション プロパティ) を含めることはできません。
            Id はおよび作成、更新、フェッチ、削除子リソースの親 i.e.CRUD とは無関係では、親 (内部使用のみ) では、CRUD は不要
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExternalChildResource (string name, ParentImplT parent, InnerModelT innerObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, !ParentImplT parent, !InnerModelT innerObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.#ctor(System.String,`3,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, parent As ParentImplT, innerObject As InnerModelT)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt; : string * 'ParentImplT * 'InnerModelT -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt; (name, parent, innerObject)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parent" Type="ParentImplT" />
        <Parameter Name="innerObject" Type="InnerModelT" />
      </Parameters>
      <Docs>
        <param name="name">この外部の子リソースの名前</param>
        <param name="parent">この外部の子リソースの親への参照します。</param>
        <param name="innerObject">この外部の子リソースを表す内部オブジェクトへの参照します。</param>
        <summary>
            外部の子リソースのメモリ内のインスタンスを作成します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChildResourceKey">
      <MemberSignature Language="C#" Value="public virtual string ChildResourceKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ChildResourceKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.ChildResourceKey" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ChildResourceKey As String" />
      <MemberSignature Language="F#" Value="member this.ChildResourceKey : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;.ChildResourceKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;FluentModelT&gt; CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!FluentModelT&gt; CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="externalChildResource.CreateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;FluentModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            この外部の子リソースを作成します。
            </summary>
        <returns>作成アクションを追跡するタスク</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="externalChildResource.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            この外部の子リソースを削除します。
            </summary>
        <returns>削除操作を追跡するタスク</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInnerAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;InnerModelT&gt; GetInnerAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!InnerModelT&gt; GetInnerAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.GetInnerAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetInnerAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'InnerModelT&gt;" Usage="externalChildResource.GetInnerAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;InnerModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public override string Name ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string Name() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.Name" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Name () As String" />
      <MemberSignature Language="F#" Value="override this.Name : unit -&gt; string" Usage="externalChildResource.Name " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingOperation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation PendingOperation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation PendingOperation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.PendingOperation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingOperation As PendingOperation" />
      <MemberSignature Language="F#" Value="member this.PendingOperation : Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource&lt;'FluentModelT, 'InnerModelT, 'IParentT, #'IParentT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;.PendingOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.PendingOperation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>この子リソースと状態のインメモリ状態では、保留中の子リソースに対してアクションを表します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public virtual FluentModelT Refresh ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !FluentModelT Refresh() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.Refresh" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Refresh () As FluentModelT" />
      <MemberSignature Language="F#" Value="abstract member Refresh : unit -&gt; 'FluentModelT&#xA;override this.Refresh : unit -&gt; 'FluentModelT" Usage="externalChildResource.Refresh " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1.Refresh</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentModelT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;FluentModelT&gt; RefreshAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!FluentModelT&gt; RefreshAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.RefreshAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;&#xA;override this.RefreshAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="externalChildResource.RefreshAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1.RefreshAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4/&lt;RefreshAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;FluentModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;FluentModelT&gt; UpdateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!FluentModelT&gt; UpdateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ExternalChildResource`4.UpdateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'FluentModelT (requires 'FluentModelT : null and 'FluentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;'FluentModelT, 'IParentT&gt;)&gt;" Usage="externalChildResource.UpdateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;FluentModelT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            この外部の子リソースを更新します。
            </summary>
        <returns>[更新] 操作を追跡するタスク</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>