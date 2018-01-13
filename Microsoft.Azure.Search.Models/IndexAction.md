<Type Name="IndexAction" FullName="Microsoft.Azure.Search.Models.IndexAction">
  <TypeSignature Language="C#" Value="public class IndexAction : Microsoft.Azure.Search.Models.IndexActionBase&lt;Microsoft.Azure.Search.Models.Document&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexAction extends Microsoft.Azure.Search.Models.IndexActionBase`1&lt;class Microsoft.Azure.Search.Models.Document&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexAction" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexAction&#xA;Inherits IndexActionBase(Of Document)" />
  <TypeSignature Language="F#" Value="type IndexAction = class&#xA;    inherit IndexActionBase&lt;Document&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.IndexActionBase&lt;Microsoft.Azure.Search.Models.Document&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Search.Models.Document</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ドキュメントで機能するインデックス アクションを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Delete (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Delete(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Delete(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Delete document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document">ドキュメントを削除します。キー以外のフィールドは無視されます。</param>
        <summary>
            ドキュメントを削除するためには、新しい IndexAction を作成します。
            </summary>
        <returns>新しい IndexAction です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Delete (string keyName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Delete(string keyName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Delete(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete (keyName As String, keyValue As String) As IndexAction" />
      <MemberSignature Language="F#" Value="static member Delete : string * string -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Delete (keyName, keyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName">インデックスのキー フィールドの名前。</param>
        <param name="keyValue">削除するドキュメントのキー。</param>
        <summary>
            ドキュメントを削除するためには、新しい IndexAction を作成します。
            </summary>
        <returns>新しい IndexAction です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; Delete&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; Delete&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Delete``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member Delete : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.Delete document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックス内のドキュメントとして格納できます。
            </typeparam>
        <param name="document">ドキュメントを削除します。キー以外のフィールドは無視されます。</param>
        <summary>
            ドキュメントを削除するためには、新しい IndexAction を作成します。
            </summary>
        <returns>新しい IndexAction です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Merge (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Merge(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Merge(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member Merge : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Merge document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document">ドキュメントをマージします。変更するフィールドのみを設定します。</param>
        <summary>
            インデックス内の既存のドキュメントにドキュメントをマージするためには、新しい IndexAction を作成します。
            </summary>
        <returns>新しい IndexAction です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; Merge&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; Merge&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Merge``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Merge(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member Merge : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.Merge document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックス内のドキュメントとして格納できます。
            </typeparam>
        <param name="document">ドキュメントをマージします。変更するプロパティだけを設定します。</param>
        <summary>
            インデックス内の既存のドキュメントにドキュメントをマージするためには、新しい IndexAction を作成します。
            </summary>
        <returns>新しい IndexAction です。</returns>
        <remarks>
            T 型に null 非許容の値に型指定されたプロパティが含まれている場合、これらのプロパティが正しくマージされない可能性があります。 このようなプロパティを設定しない場合、既定値 (たとえば、int の場合は 0) または false の bool、これはこれが意図でない場合でも、インデックスに現在格納されているプロパティの値を上書きに自動的がかかります。 このため、強くお勧め常に T 型で null 値許容値型のプロパティを宣言すること
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeOrUpload">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction MergeOrUpload (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction MergeOrUpload(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member MergeOrUpload : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document">マージまたはアップロードするドキュメントです。</param>
        <summary>
            ドキュメントをアップロードしてから、インデックス、またはインデックスに既に存在する場合、既存のドキュメントへのマージを新しい IndexAction を作成します。
            </summary>
        <returns>新しい IndexAction です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeOrUpload&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; MergeOrUpload&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; MergeOrUpload&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function MergeOrUpload(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member MergeOrUpload : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.MergeOrUpload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックス内のドキュメントとして格納できます。
            </typeparam>
        <param name="document">マージまたはアップロードするドキュメントです。</param>
        <summary>
            ドキュメントをアップロードしてから、インデックス、またはインデックスに既に存在する場合、既存のドキュメントへのマージを新しい IndexAction を作成します。
            </summary>
        <returns>新しい IndexAction です。</returns>
        <remarks>
            T 型に null 非許容の値に型指定されたプロパティが含まれている場合、これらのプロパティが正しくマージされない可能性があります。 このようなプロパティを設定しない場合、既定値 (たとえば、int の場合は 0) または false の bool、これはこれが意図でない場合でも、インデックスに現在格納されているプロパティの値を上書きに自動的がかかります。 このため、強くお勧め常に T 型で null 値許容値型のプロパティを宣言すること
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction Upload (Microsoft.Azure.Search.Models.Document document);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction Upload(class Microsoft.Azure.Search.Models.Document document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Upload(Microsoft.Azure.Search.Models.Document)" />
      <MemberSignature Language="F#" Value="static member Upload : Microsoft.Azure.Search.Models.Document -&gt; Microsoft.Azure.Search.Models.IndexAction" Usage="Microsoft.Azure.Search.Models.IndexAction.Upload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="Microsoft.Azure.Search.Models.Document" />
      </Parameters>
      <Docs>
        <param name="document">アップロードするドキュメントです。</param>
        <summary>
            インデックスにドキュメントをアップロードするためには、新しい IndexAction を作成します。
            </summary>
        <returns>新しい IndexAction です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexAction&lt;T&gt; Upload&lt;T&gt; (T document) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexAction`1&lt;!!T&gt; Upload&lt;class T&gt;(!!T document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexAction.Upload``1(``0)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Upload(Of T As Class) (document As T) As IndexAction(Of T)" />
      <MemberSignature Language="F#" Value="static member Upload : 'T -&gt; Microsoft.Azure.Search.Models.IndexAction&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.Models.IndexAction.Upload document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexAction&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="document" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            インデックス スキーマにマップされる CLR 型。 この型のインスタンスは、インデックス内のドキュメントとして格納できます。
            </typeparam>
        <param name="document">アップロードするドキュメントです。</param>
        <summary>
            インデックスにドキュメントをアップロードするためには、新しい IndexAction を作成します。
            </summary>
        <returns>新しい IndexAction です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>