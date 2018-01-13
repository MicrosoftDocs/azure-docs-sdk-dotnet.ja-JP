<Type Name="IndexActionBase&lt;T&gt;" FullName="Microsoft.Azure.Search.Models.IndexActionBase&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class IndexActionBase&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit IndexActionBase`1&lt;class T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexActionBase`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class IndexActionBase(Of T)" />
  <TypeSignature Language="F#" Value="type IndexActionBase&lt;'T (requires 'T : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックス内のドキュメントとして格納できます。
            </typeparam>
    <summary>
            ドキュメントを操作するインデックス アクションの抽象基本クラス。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected IndexActionBase (Microsoft.Azure.Search.Models.IndexActionType actionType, T document);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Search.Models.IndexActionType actionType, !T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexActionBase`1.#ctor(Microsoft.Azure.Search.Models.IndexActionType,`0)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (actionType As IndexActionType, document As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexActionBase&lt;'T (requires 'T : null)&gt; : Microsoft.Azure.Search.Models.IndexActionType * 'T -&gt; Microsoft.Azure.Search.Models.IndexActionBase&lt;'T (requires 'T : null)&gt;" Usage="new Microsoft.Azure.Search.Models.IndexActionBase&lt;'T (requires 'T : null)&gt; (actionType, document)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionType" Type="Microsoft.Azure.Search.Models.IndexActionType" />
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <param name="actionType">ドキュメントに対して実行するアクションの種類。</param>
        <param name="document">アクションを実行するドキュメントです。</param>
        <summary>
            指定されたアクションの種類は使用して IndexActionBase クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.IndexActionType ActionType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.IndexActionType ActionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexActionBase`1.ActionType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActionType As IndexActionType" />
      <MemberSignature Language="F#" Value="member this.ActionType : Microsoft.Azure.Search.Models.IndexActionType" Usage="Microsoft.Azure.Search.Models.IndexActionBase&lt;'T (requires 'T : null)&gt;.ActionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexActionType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            インデックスのバッチ内のドキュメントに対して実行するアクションを示す値を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Document">
      <MemberSignature Language="C#" Value="public T Document { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Document" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexActionBase`1.Document" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Document As T" />
      <MemberSignature Language="F#" Value="member this.Document : 'T" Usage="Microsoft.Azure.Search.Models.IndexActionBase&lt;'T (requires 'T : null)&gt;.Document" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ドキュメントを取得しますが、アクションが実行されます。キー以外のフィールドには、削除操作は無視されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>