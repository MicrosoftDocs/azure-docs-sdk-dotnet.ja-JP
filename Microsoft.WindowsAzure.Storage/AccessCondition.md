<Type Name="AccessCondition" FullName="Microsoft.WindowsAzure.Storage.AccessCondition">
  <TypeSignature Language="C#" Value="public sealed class AccessCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AccessCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.AccessCondition" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AccessCondition" />
  <TypeSignature Language="F#" Value="type AccessCondition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ストレージ サービスに対して操作をするためのアクセス条件のセットを表します。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AccessCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AccessCondition Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.AccessCondition Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As AccessCondition" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="accessCondition.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            現在のアクセス条件の簡易コピーを提供します。
            </summary>
        <returns>簡易コピー、<see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />オブジェクト</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateEmptyCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateEmptyCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateEmptyCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateEmptyCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateEmptyCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateEmptyCondition : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateEmptyCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            空のアクセス条件を構築します。
            </summary>
        <returns>空の <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfAppendPositionEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfAppendPositionEqualCondition (long appendPosition);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfAppendPositionEqualCondition(int64 appendPosition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfAppendPositionEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfAppendPositionEqualCondition (appendPosition As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfAppendPositionEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfAppendPositionEqualCondition appendPosition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appendPosition" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="appendPosition">Blob の現在の終了位置と比較するオフセットを指定する整数。</param>
        <summary>
            追加 blob の末尾の位置が指定した値に等しい場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />を比較するオフセットを表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfExistsCondition : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            リソースが存在する場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />リソースが存在する条件を表すオブジェクト。</returns>
        <remarks>このアクセス条件を設定を含める HTTP 要求を変更<i>If-match</i>条件ヘッダー。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMatchCondition (string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMatchCondition(string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfMatchCondition (etag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfMatchCondition : string -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMatchCondition etag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="etag">リソースの ETag と照合する ETag 値です。</param>
        <summary>
            リソースの ETag 値が指定された ETag 値と一致する場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> If-match 条件を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfMaxSizeLessThanOrEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMaxSizeLessThanOrEqualCondition (long maxSize);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfMaxSizeLessThanOrEqualCondition(int64 maxSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMaxSizeLessThanOrEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfMaxSizeLessThanOrEqualCondition (maxSize As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfMaxSizeLessThanOrEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfMaxSizeLessThanOrEqualCondition maxSize" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxSize" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="maxSize">新しいブロックをコミットするときは、(バイト単位)、blob の最大許容サイズを指定する整数。</param>
        <summary>
            ブロックをコミットした後に、追加 blob のサイズは、指定した値に等しいまたはそれよりも小さい場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />最大許容サイズを表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfModifiedSinceCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfModifiedSinceCondition (DateTimeOffset modifiedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfModifiedSinceCondition(valuetype System.DateTimeOffset modifiedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfModifiedSinceCondition(System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfModifiedSinceCondition (modifiedTime As DateTimeOffset) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfModifiedSinceCondition : DateTimeOffset -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfModifiedSinceCondition modifiedTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="modifiedTime" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="modifiedTime">A<see cref="T:System.DateTimeOffset" />以降、リソース変更された時間を指定する値。</param>
        <summary>
            指定した時刻以降にリソースが変更された場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />場合-変更のための条件を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNoneMatchCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNoneMatchCondition (string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNoneMatchCondition(string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNoneMatchCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNoneMatchCondition (etag As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNoneMatchCondition : string -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNoneMatchCondition etag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="etag">リソースの ETag と照合する ETag 値または<c>"*"</c>リソースが存在しないことを要求します。</param>
        <summary>
            リソースの ETag 値が指定された ETag 値に一致しない場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />なし-If-match 条件を表すオブジェクト。</returns>
        <remarks>
            場合<c>"*"</c>が指定されて、<paramref name="etag" />パラメーターをこの条件は、リソースが存在しないことが必要です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNotExistsCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotExistsCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotExistsCondition() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNotExistsCondition () As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNotExistsCondition : unit -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotExistsCondition " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            リソースが存在しない場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />リソースが存在しない場合、条件を表すオブジェクト。</returns>
        <remarks>このアクセス条件を設定を含める HTTP 要求を変更<i>なし-If-match</i>条件ヘッダー。</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfNotModifiedSinceCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotModifiedSinceCondition (DateTimeOffset modifiedTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfNotModifiedSinceCondition(valuetype System.DateTimeOffset modifiedTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotModifiedSinceCondition(System.DateTimeOffset)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfNotModifiedSinceCondition (modifiedTime As DateTimeOffset) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfNotModifiedSinceCondition : DateTimeOffset -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfNotModifiedSinceCondition modifiedTime" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="modifiedTime" Type="System.DateTimeOffset" />
      </Parameters>
      <Docs>
        <param name="modifiedTime">A<see cref="T:System.DateTimeOffset" />以降、リソース必要がありますが変更されていない時刻を指定する値。</param>
        <summary>
            指定した時刻以降、リソースが変更されていない場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />場合は、未変更の状態-以降条件を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfSequenceNumberEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberEqualCondition (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberEqualCondition(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfSequenceNumberEqualCondition (sequenceNumber As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfSequenceNumberEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberEqualCondition sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">現在のシーケンス番号と比較する値。</param>
        <summary>
            リソースの現在のシーケンス番号が指定した値に等しい場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />場合にシーケンス番号 EQ 条件を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfSequenceNumberLessThanCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanCondition (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanCondition(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfSequenceNumberLessThanCondition (sequenceNumber As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfSequenceNumberLessThanCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanCondition sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">現在のシーケンス番号と比較する値。</param>
        <summary>
            リソースの現在のシーケンス番号が指定された値より小さい場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />場合にシーケンス番号 LT 条件を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateIfSequenceNumberLessThanOrEqualCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanOrEqualCondition (long sequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateIfSequenceNumberLessThanOrEqualCondition(int64 sequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanOrEqualCondition(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateIfSequenceNumberLessThanOrEqualCondition (sequenceNumber As Long) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateIfSequenceNumberLessThanOrEqualCondition : int64 -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateIfSequenceNumberLessThanOrEqualCondition sequenceNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="sequenceNumber">現在のシーケンス番号と比較する値。</param>
        <summary>
            リソースの現在のシーケンス番号が指定した値に等しいまたはそれよりも小さい場合にのみ操作が実行されるように、アクセス条件を構築します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />場合にシーケンス番号 LE 条件を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateLeaseCondition">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Storage.AccessCondition GenerateLeaseCondition (string leaseId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Storage.AccessCondition GenerateLeaseCondition(string leaseId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.AccessCondition.GenerateLeaseCondition(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateLeaseCondition (leaseId As String) As AccessCondition" />
      <MemberSignature Language="F#" Value="static member GenerateLeaseCondition : string -&gt; Microsoft.WindowsAzure.Storage.AccessCondition" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.GenerateLeaseCondition leaseId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leaseId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leaseId">リソースのリース ID と比較するリース ID です。</param>
        <summary>
            リソースのリース ID が指定されたリース ID と一致する場合にのみ操作が実行されるように、アクセス条件を作成します。
            </summary>
        <returns><see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" />リース条件を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfAppendPositionEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfAppendPositionEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfAppendPositionEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfAppendPositionEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfAppendPositionEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfAppendPositionEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfAppendPositionEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または追加 blob にブロックをコミットするときにチェックするバイト オフセットを指定する条件の値を設定します。
            この追加は、終了位置がこの値に等しい場合にのみ成功します。 
            </summary>
        <value>追加の位置の番号の場合、または<c>null</c>値が設定されていない場合。</value>
        <remarks>この条件は、追加 blob にのみ適用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMatchETag">
      <MemberSignature Language="C#" Value="public string IfMatchETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfMatchETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMatchETag As String" />
      <MemberSignature Language="F#" Value="member this.IfMatchETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定した ETag と一致するが、指定されたリソースの ETag を指定する条件の ETag 値を設定します。
            </summary>
        <value>ETag 値を含む文字列または<c>"*"</c>任意の ETag が一致するようにします。 場合<c>null</c>条件が存在しません。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMaxSizeLessThanOrEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfMaxSizeLessThanOrEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfMaxSizeLessThanOrEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMaxSizeLessThanOrEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMaxSizeLessThanOrEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfMaxSizeLessThanOrEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfMaxSizeLessThanOrEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または新しいブロックがコミットされるときに、追加 blob の許容される最大サイズを指定する条件の値を設定します。 この追加は、追加操作の後に blob のサイズが指定されたサイズに等しいまたはそれよりも小さい場合にのみ成功します。
            </summary>
        <value>最大サイズ (バイト単位) または<c>null</c>値が設定されていない場合。</value>
        <remarks>この条件は、追加 blob にのみ適用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfModifiedSinceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; IfModifiedSinceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; IfModifiedSinceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfModifiedSinceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property IfModifiedSinceTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.IfModifiedSinceTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfModifiedSinceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、<see cref="T:System.DateTimeOffset" />以降、リソースが変更された時刻を指定する条件の値。
            </summary>
        <value>A <see cref="T:System.DateTimeOffset" /> (UTC) で指定された値または<c>null</c>条件が存在しない場合。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNoneMatchETag">
      <MemberSignature Language="C#" Value="public string IfNoneMatchETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfNoneMatchETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNoneMatchETag" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNoneMatchETag As String" />
      <MemberSignature Language="F#" Value="member this.IfNoneMatchETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfNoneMatchETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または指定した ETag が、指定したリソースの ETag と一致する必要がありますを指定する条件の ETag 値を設定します。
            </summary>
        <value>ETag 値を含む文字列または<c>"*"</c>任意の ETag が一致するようにします。 場合<c>null</c>条件が存在しません。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNotModifiedSinceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; IfNotModifiedSinceTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; IfNotModifiedSinceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNotModifiedSinceTime" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNotModifiedSinceTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.IfNotModifiedSinceTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfNotModifiedSinceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、<see cref="T:System.DateTimeOffset" />以降、リソースが変更されていない時間を指定する条件の値。
            </summary>
        <value>A <see cref="T:System.DateTimeOffset" /> (UTC) で指定された値または<c>null</c>条件が存在しない場合。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfSequenceNumberEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfSequenceNumberEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfSequenceNumberEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfSequenceNumberEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfSequenceNumberEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または現在のシーケンス番号が指定された値と同じにする必要がありますを指定する条件の値を設定します。
            </summary>
        <value>シーケンス番号、または<c>null</c>条件が存在しない場合。</value>
        <remarks>この条件は、ページ blob にのみ適用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfSequenceNumberLessThan">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfSequenceNumberLessThan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfSequenceNumberLessThan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThan" />
      <MemberSignature Language="VB.NET" Value="Public Property IfSequenceNumberLessThan As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfSequenceNumberLessThan : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または現在のシーケンス番号が指定した値より小さくなければならないことを指定する条件の値を設定します。
            </summary>
        <value>シーケンス番号、または<c>null</c>条件が存在しない場合。</value>
        <remarks>この条件は、ページ blob にのみ適用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfSequenceNumberLessThanOrEqual">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; IfSequenceNumberLessThanOrEqual { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; IfSequenceNumberLessThanOrEqual" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThanOrEqual" />
      <MemberSignature Language="VB.NET" Value="Public Property IfSequenceNumberLessThanOrEqual As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.IfSequenceNumberLessThanOrEqual : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.IfSequenceNumberLessThanOrEqual" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定を指定する条件の値であり、現在のシーケンス番号は、指定された値以下である必要があります。
            </summary>
        <value>シーケンス番号、または<c>null</c>条件が存在しない場合。</value>
        <remarks>この条件は、ページ blob にのみ適用されます。</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseId">
      <MemberSignature Language="C#" Value="public string LeaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LeaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.AccessCondition.LeaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseId As String" />
      <MemberSignature Language="F#" Value="member this.LeaseId : string with get, set" Usage="Microsoft.WindowsAzure.Storage.AccessCondition.LeaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはリソースのリースと一致するリース ID を設定します。
            </summary>
        <value>リース ID を表す文字列または<c>null</c>条件が存在しない場合。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>