<Type Name="AccessCondition" FullName="Microsoft.Azure.Search.Models.AccessCondition">
  <TypeSignature Language="C#" Value="public class AccessCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AccessCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.AccessCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class AccessCondition" />
  <TypeSignature Language="F#" Value="type AccessCondition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            一連の操作に追加のパラメーターです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AccessCondition クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessCondition (string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional ifMatch As String = null, Optional ifNoneMatch As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.AccessCondition : string * string -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="new Microsoft.Azure.Search.Models.AccessCondition (ifMatch, ifNoneMatch)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ifMatch">If-match 条件を定義します。 操作は、サーバー上の ETag がこの値に一致する場合にのみ実行されます。</param>
        <param name="ifNoneMatch">None-If-match 条件を定義します。 サーバーの ETag が、この値と一致しない場合にのみ、操作が実行されます。</param>
        <summary>
            AccessCondition クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateEmptyCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateEmptyCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateEmptyCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateEmptyCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateEmptyCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateEmptyCondition : unit -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateEmptyCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            空のアクセス条件を構築します。
            </summary>
        <returns>空の <see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfExistsCondition : unit -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            リソースが存在する場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Search.Models.AccessCondition" />リソースが存在する条件を表すオブジェクト。</returns>
        <remarks>このアクセス条件を設定を含める HTTP 要求を変更<i>If-match</i>条件付きのヘッダーに設定されて<c>"*"</c>です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfMatchCondition (string eTag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfMatchCondition(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfMatchCondition (eTag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfMatchCondition : string -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfMatchCondition eTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag">リソースの ETag と照合する ETag 値です。</param>
        <summary>
            リソースの現在の ETag 値が指定された ETag 値と一致する場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> If-match 条件を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNoneMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfNoneMatchCondition (string eTag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfNoneMatchCondition(string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNoneMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNoneMatchCondition (eTag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNoneMatchCondition : string -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNoneMatchCondition eTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eTag">リソースの ETag と照合する ETag 値です。</param>
        <summary>
            リソースの現在の ETag 値が指定された ETag 値に一致しない場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Search.Models.AccessCondition" />なし-If-match 条件を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNotExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition GenerateIfNotExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition GenerateIfNotExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNotExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNotExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNotExistsCondition : unit -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.GenerateIfNotExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            リソースが存在しない場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Search.Models.AccessCondition" />リソースが存在しない場合、条件を表すオブジェクト。</returns>
        <remarks>このアクセス条件を設定を含める HTTP 要求を変更<i>なし-If-match</i>条件付きのヘッダーに設定されて<c>"*"</c>です。</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMatch">
      <MemberSignature Language="C#" Value="public string IfMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AccessCondition.IfMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMatch As String" />
      <MemberSignature Language="F#" Value="member this.IfMatch : string with get, set" Usage="Microsoft.Azure.Search.Models.AccessCondition.IfMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、If-match 条件を定義します。 操作は、サーバー上の ETag がこの値に一致する場合にのみ実行されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNoneMatch">
      <MemberSignature Language="C#" Value="public string IfNoneMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfNoneMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.AccessCondition.IfNoneMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNoneMatch As String" />
      <MemberSignature Language="F#" Value="member this.IfNoneMatch : string with get, set" Usage="Microsoft.Azure.Search.Models.AccessCondition.IfNoneMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、[なし]-If-match 条件を定義します。 サーバーの ETag が、この値と一致しない場合にのみ、操作が実行されます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNotChanged">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AccessCondition IfNotChanged (Microsoft.Azure.Search.Models.IResourceWithETag resource);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AccessCondition IfNotChanged(class Microsoft.Azure.Search.Models.IResourceWithETag resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.AccessCondition.IfNotChanged(Microsoft.Azure.Search.Models.IResourceWithETag)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IfNotChanged (resource As IResourceWithETag) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member IfNotChanged : Microsoft.Azure.Search.Models.IResourceWithETag -&gt; Microsoft.Azure.Search.Models.AccessCondition" Usage="Microsoft.Azure.Search.Models.AccessCondition.IfNotChanged resource" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="Microsoft.Azure.Search.Models.IResourceWithETag" />
      </Parameters>
      <Docs>
        <param name="resource">使用したリソース、リソースの ETag と照合する ETag 値です。</param>
        <summary>
            リソースの現在の ETag 値が指定されたリソースの ETag 値と一致する場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.Azure.Search.Models.AccessCondition" /> If-match 条件を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>