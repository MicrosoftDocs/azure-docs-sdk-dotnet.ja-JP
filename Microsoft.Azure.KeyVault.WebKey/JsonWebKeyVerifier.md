<Type Name="JsonWebKeyVerifier" FullName="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier">
  <TypeSignature Language="C#" Value="public abstract class JsonWebKeyVerifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit JsonWebKeyVerifier extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class JsonWebKeyVerifier" />
  <TypeSignature Language="F#" Value="type JsonWebKeyVerifier = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            クラスのインスタンスを検証する<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />キーの種類に従ってします。 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected JsonWebKeyVerifier (string kty);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string kty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (kty As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier : string -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" Usage="new Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier kty" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kty" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="kty">この検証が適用するキーの種類を示します。</param>
        <summary>
            指定された値の設定の新しいインスタンスを初期化、<see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />プロパティです。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">指定した値が場合<code>null</code>、空または空白文字。</exception>
        <exception cref="T:System.ArgumentException">場合は、指定された値には、無効な文字が含まれています。</exception>
      </Docs>
    </Member>
    <Member MemberName="AddCompatibleOperations">
      <MemberSignature Language="C#" Value="protected abstract void AddCompatibleOperations (System.Collections.Generic.ICollection&lt;string&gt; compatibleOperations);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void AddCompatibleOperations(class System.Collections.Generic.ICollection`1&lt;string&gt; compatibleOperations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddCompatibleOperations(System.Collections.Generic.ICollection{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub AddCompatibleOperations (compatibleOperations As ICollection(Of String))" />
      <MemberSignature Language="F#" Value="abstract member AddCompatibleOperations : System.Collections.Generic.ICollection&lt;string&gt; -&gt; unit" Usage="jsonWebKeyVerifier.AddCompatibleOperations compatibleOperations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="compatibleOperations" Type="System.Collections.Generic.ICollection&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="compatibleOperations">To be added.</param>
        <summary>
            型を持つがこのオブジェクトによって処理されるキーを持つ実行可能なすべての操作を指定されたコレクションに追加します。
            </summary>
        <remarks>To be added.</remarks>
        <see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyOperation.Sign" />
        <see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyOperation.Verify" />
      </Docs>
    </Member>
    <Member MemberName="AddItem&lt;T&gt;">
      <MemberSignature Language="C#" Value="protected static void AddItem&lt;T&gt; (ref System.Collections.Generic.ICollection&lt;T&gt; items, T newItem);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig void AddItem&lt;T&gt;(class System.Collections.Generic.ICollection`1&lt;!!T&gt;&amp; items, !!T newItem) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddItem``1(System.Collections.Generic.ICollection{``0}@,``0)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Sub AddItem(Of T) (ByRef items As ICollection(Of T), newItem As T)" />
      <MemberSignature Language="F#" Value="static member AddItem :  * 'T -&gt; unit" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddItem (items, newItem)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="items" Type="System.Collections.Generic.ICollection&lt;T&gt;&amp;" RefType="ref" />
        <Parameter Name="newItem" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="items">To be added.</param>
        <param name="newItem">To be added.</param>
        <summary>
            コレクションを作成する (必要な場合) の操作を結合するヘルパー メソッドを項目を追加するとします。
            </summary>
        <remarks>To be added.</remarks>
        <see cref="T:System.Collections.Generic.List`1" />
      </Docs>
    </Member>
    <Member MemberName="AddUsedProperties">
      <MemberSignature Language="C#" Value="protected abstract void AddUsedProperties (System.Collections.Generic.ICollection&lt;string&gt; usedProperties);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void AddUsedProperties(class System.Collections.Generic.ICollection`1&lt;string&gt; usedProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.AddUsedProperties(System.Collections.Generic.ICollection{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub AddUsedProperties (usedProperties As ICollection(Of String))" />
      <MemberSignature Language="F#" Value="abstract member AddUsedProperties : System.Collections.Generic.ICollection&lt;string&gt; -&gt; unit" Usage="jsonWebKeyVerifier.AddUsedProperties usedProperties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="usedProperties" Type="System.Collections.Generic.ICollection&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="usedProperties">To be added.</param>
        <summary>
            キーの型はこのオブジェクトによって処理に使用されるすべての JsonWebKey プロパティを指定されたコレクションに追加します。
            </summary>
        <remarks>To be added.</remarks>
        <para>このメソッドが JSON プロパティ名をなど、追加する必要があります<code>"crv"</code>、 <code>"p"</code>, などです。C# のプロパティ名は追加しないでください。</para>
        <para>このメソッドを追加する必要はありません<code>"kid"</code>、<code>"kty"</code>と<code>"key_ops"</code>です。
            アプリケーションのプロパティは、すべてのキーに有用であると見なされます。</para>
      </Docs>
    </Member>
    <Member MemberName="GetVerifier">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier GetVerifier (string kty);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier GetVerifier(string kty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.GetVerifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetVerifier (kty As String) As JsonWebKeyVerifier" />
      <MemberSignature Language="F#" Value="static member GetVerifier : string -&gt; Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.GetVerifier kty" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kty" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="kty">To be added.</param>
        <summary>
            Kty 値が登録されていない場合は、null、または、指定した kty 値の登録された、検証機能を返します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyType" />
        <altmember cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />
      </Docs>
    </Member>
    <Member MemberName="HasSecretKey">
      <MemberSignature Language="C#" Value="public abstract bool HasSecretKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasSecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.HasSecretKey" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property HasSecretKey As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasSecretKey : bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.HasSecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このオブジェクトによって検証キーの種類にハードウェア キー トークンなど、シークレットのコンポーネントが含まれているかどうかに指示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code>true</code>
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      </Docs>
    </Member>
    <Member MemberName="IsAnyPrivateKeyParamSpecified">
      <MemberSignature Language="C#" Value="public virtual bool IsAnyPrivateKeyParamSpecified (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; specifiedProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsAnyPrivateKeyParamSpecified(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; specifiedProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsAnyPrivateKeyParamSpecified(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsAnyPrivateKeyParamSpecified (webKey As JsonWebKey, ByRef specifiedProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsAnyPrivateKeyParamSpecified : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsAnyPrivateKeyParamSpecified : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsAnyPrivateKeyParamSpecified (webKey, specifiedProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="specifiedProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">確認するインスタンス。</param>
        <param name="specifiedProps">指定したプロパティの一覧を示す変数への参照。 呼び出し元が変数に設定する必要があります<code>null</code>し、このメソッドが戻る場合にのみ、値を調べて<code>true</code>です。</param>
        <summary>
            かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、秘密キーを表す 1 つまたは複数のプロパティの値が含まれています。 
            </summary>
        <returns>
          <code>true</code>秘密キーを記述するには、少なくとも 1 つのプロパティに値が見つかった場合<code>false</code>それ以外の場合。</returns>
        <remarks>To be added.</remarks>
        <para>このメソッドは、偶発的な漏えいから秘密キー マテリアルを保護するのに使用されます。</para>
        <para>秘密キー プロパティ (キーの種類) を指定しないかどうか、インスタンスで、メソッドが返す必要があります。
            <code>false</code>変更しないと、<paramref name="specifiedProps" />パラメーター。</para>
        <para>1 つまたは複数の秘密キーのプロパティが指定されているかどうか、メソッドが返す必要があります<code>true</code>し、必要に応じて設定<paramref name="specifiedProps" />値を持つ - 通常、 <see cref="T:System.Collections.Generic.List`1" /> -指定したプロパティを含むです。</para>
      </Docs>
    </Member>
    <Member MemberName="IsOperationCompatible">
      <MemberSignature Language="C#" Value="public bool IsOperationCompatible (string opName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsOperationCompatible(string opName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsOperationCompatible(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsOperationCompatible (opName As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOperationCompatible : string -&gt; bool" Usage="jsonWebKeyVerifier.IsOperationCompatible opName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="opName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="opName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOperationValid">
      <MemberSignature Language="C#" Value="public static bool IsOperationValid (string opName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsOperationValid(string opName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsOperationValid(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsOperationValid (opName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsOperationValid : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsOperationValid opName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="opName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="opName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivateKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsPrivateKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPrivateKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPrivateKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPrivateKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPrivateKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPrivateKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">To be added.</param>
        <param name="missingProps">To be added.</param>
        <summary>
            同じ<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />、ですが、秘密キーです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrivateKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsPrivateKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPrivateKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPrivateKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPrivateKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPrivateKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPrivateKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">To be added.</param>
        <param name="errorMsg">To be added.</param>
        <summary>
            同じ<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />、ですが、秘密キーです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPropertyUsed">
      <MemberSignature Language="C#" Value="public bool IsPropertyUsed (string propName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsPropertyUsed(string propName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPropertyUsed(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function IsPropertyUsed (propName As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPropertyUsed : string -&gt; bool" Usage="jsonWebKeyVerifier.IsPropertyUsed propName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propName">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPublicKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsPublicKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPublicKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPublicKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPublicKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPublicKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPublicKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">確認するインスタンス。</param>
        <param name="missingProps">不足しているプロパティの一覧を示す変数への参照。 呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</param>
        <summary>
            かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、公開キーを表すプロパティに値が含まれています。 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>かどうかは、インスタンスで必要な公開キーのすべてのプロパティ (キーの種類) が指定された、メソッドが返す必要があります。
            <code>true</code>変更しないと、<paramref name="missingProps" />パラメーター。</para>
        <para>一部のパブリック キー プロパティがないメソッドが返す必要があります<code>false</code>設定と<paramref name="missingProps" />値を持つ - 通常、 <see cref="T:System.Collections.Generic.List`1" /> -欠損しているすべてのプロパティを含むです。</para>
      </Docs>
    </Member>
    <Member MemberName="IsPublicKeyCrypto">
      <MemberSignature Language="C#" Value="public abstract bool IsPublicKeyCrypto { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPublicKeyCrypto" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyCrypto" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property IsPublicKeyCrypto As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPublicKeyCrypto : bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyCrypto" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このオブジェクトによって検証キーの型が公開キー アルゴリズムをサポートしているかどうかに指示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code>true</code>
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPrivateKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      </Docs>
    </Member>
    <Member MemberName="IsPublicKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsPublicKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsPublicKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsPublicKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsPublicKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsPublicKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsPublicKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">確認するインスタンス。</param>
        <param name="errorMsg">エラー メッセージを格納する変数への参照。 呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</param>
        <summary>
            かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、可能性のある有効な公開キーが含まれています (「解説」を参照してください)。 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>キーを完全に検証すると、リソースの量の unfeasable がかかる場合があります、ために、このメソッドは明らかな問題を確認するだけあります。 指針としては、定数時間で実行する場合、コードがその明らかな問題をのみ検証すると言います。
            何もしない実装で完全に有効と戻り値だけである<code>true</code>です。</para>
        <para>このメソッドが想定する<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />が呼び出され、返される<code>true</code>です。 これは、必要なプロパティが存在する、もう一度テストしません。 スローする可能性が<see cref="T:System.NullReferenceException" />場合は、呼び出し元が認識されない<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsPublicKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />返す<code>true</code>最初。</para>
        <para>このメソッドを返す必要があるかどうか valiation コードが検出されない問題、<code>true</code>の値を変更することがなく<paramref name="errorMsg" />です。</para>
        <para>いくつかの問題が見つからないかどうかは、このメソッドが返す必要があります<code>false</code>で詳細を確認し、<paramref name="errorMsg" />パラメーター。</para>
      </Docs>
    </Member>
    <Member MemberName="IsSecretKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsSecretKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSecretKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSecretKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSecretKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSecretKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSecretKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">確認するインスタンス。</param>
        <param name="missingProps">不足しているプロパティの一覧を示す変数への参照。 呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</param>
        <summary>
            かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、秘密キーを表すプロパティに値が含まれています。 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>かどうかは、インスタンスで必要な秘密キーのすべてのプロパティ (キーの種類) が指定された、メソッドが返す必要があります。
            <code>true</code>変更しないと、<paramref name="missingProps" />パラメーター。</para>
        <para>一部のプロパティがないメソッドが返す必要があります<code>false</code>設定と<paramref name="missingProps" />値 - 通常、 <see cref="T:System.Collections.Generic.List`1" /> -欠損しているすべてのプロパティを含むです。</para>
      </Docs>
    </Member>
    <Member MemberName="IsSecretKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsSecretKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSecretKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSecretKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSecretKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSecretKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSecretKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">確認するインスタンス。</param>
        <param name="errorMsg">エラー メッセージを格納する変数への参照。 呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</param>
        <summary>
            かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、可能性のある有効な秘密キーが含まれています (「解説」を参照してください)。 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>キーを完全に検証すると、リソースの量の unfeasable がかかる場合があります、ために、このメソッドは明らかな問題を確認するだけあります。 指針としては、定数時間で実行する場合、コードがその明らかな問題をのみ検証すると言います。
            何もしない実装で完全に有効と戻り値だけである<code>true</code>です。</para>
        <para>このメソッドが想定する<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />が呼び出され、返される<code>true</code>です。 これは、必要なプロパティが存在する、もう一度テストしません。 スローする可能性が<see cref="T:System.NullReferenceException" />場合は、呼び出し元が認識されない<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSecretKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />返す<code>true</code>最初。</para>
        <para>このメソッドを返す必要があるかどうか valiation コードが検出されない問題、<code>true</code>の値を変更することがなく<paramref name="errorMsg" />です。</para>
        <para>いくつかの問題が見つからないかどうかは、このメソッドが返す必要があります<code>false</code>で詳細を確認し、<paramref name="errorMsg" />パラメーター。</para>
      </Docs>
    </Member>
    <Member MemberName="IsSymmetricKeyComplete">
      <MemberSignature Language="C#" Value="public virtual bool IsSymmetricKeyComplete (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref System.Collections.Generic.ICollection&lt;string&gt; missingProps);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSymmetricKeyComplete(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, class System.Collections.Generic.ICollection`1&lt;string&gt;&amp; missingProps) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSymmetricKeyComplete (webKey As JsonWebKey, ByRef missingProps As ICollection(Of String)) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSymmetricKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSymmetricKeyComplete : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSymmetricKeyComplete (webKey, missingProps)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="missingProps" Type="System.Collections.Generic.ICollection&lt;System.String&gt;&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">確認するインスタンス。</param>
        <param name="missingProps">不足しているプロパティの一覧を示す変数への参照。 呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</param>
        <summary>
            かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、対称キーを表すプロパティに値が含まれています。 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>かどうかは、インスタンスで必要な対称キーのすべてのプロパティ (キーの種類) が指定された、メソッドが返す必要があります。
            <code>true</code>変更しないと、<paramref name="missingProps" />パラメーター。</para>
        <para>一部のプロパティがないメソッドが返す必要があります<code>false</code>設定と<paramref name="missingProps" />値 - 通常、 <see cref="T:System.Collections.Generic.List`1" /> -欠損しているすべてのプロパティを含むです。</para>
      </Docs>
    </Member>
    <Member MemberName="IsSymmetricKeyCrypto">
      <MemberSignature Language="C#" Value="public abstract bool IsSymmetricKeyCrypto { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSymmetricKeyCrypto" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyCrypto" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride ReadOnly Property IsSymmetricKeyCrypto As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSymmetricKeyCrypto : bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyCrypto" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このオブジェクトによって検証キーの種類が対称キーのアルゴリズムをサポートしているかどうかに指示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <code>true</code>
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      </Docs>
    </Member>
    <Member MemberName="IsSymmetricKeyValid">
      <MemberSignature Language="C#" Value="public virtual bool IsSymmetricKeyValid (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool IsSymmetricKeyValid(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyValid(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function IsSymmetricKeyValid (webKey As JsonWebKey, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsSymmetricKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool&#xA;override this.IsSymmetricKeyValid : Microsoft.Azure.KeyVault.WebKey.JsonWebKey *  -&gt; bool" Usage="jsonWebKeyVerifier.IsSymmetricKeyValid (webKey, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">確認するインスタンス。</param>
        <param name="errorMsg">エラー メッセージを格納する変数への参照。 呼び出し元が変数に設定する必要があります<code>null</code>、このメソッドが戻る場合にのみ、値を調べて、<code>false</code>です。</param>
        <summary>
            かどうかを指定した<see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />インスタンスには、可能性のある有効な対称キーが含まれています (「解説」を参照してください)。 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <para>キーを完全に検証すると、リソースの量の unfeasable がかかる場合があります、ために、このメソッドは明らかな問題を確認するだけあります。 指針としては、定数時間で実行する場合、コードがその明らかな問題をのみ検証すると言います。
            何もしない実装で完全に有効と戻り値だけである<code>true</code>です。</para>
        <para>このメソッドが想定する<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />が呼び出され、返される<code>true</code>です。 これは、必要なプロパティが存在する、もう一度テストしません。 スローする可能性が<see cref="T:System.NullReferenceException" />場合は、呼び出し元が認識されない<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.IsSymmetricKeyComplete(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Collections.Generic.ICollection{System.String}@)" />返す<code>true</code>最初。</para>
        <para>このメソッドを返す必要があるかどうか valiation コードが検出されない問題、<code>true</code>の値を変更することがなく<paramref name="errorMsg" />です。</para>
        <para>いくつかの問題が見つからないかどうかは、このメソッドが返す必要があります<code>false</code>で詳細を確認し、<paramref name="errorMsg" />パラメーター。</para>
      </Docs>
    </Member>
    <Member MemberName="Kty">
      <MemberSignature Language="C#" Value="public string Kty { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kty As String" />
      <MemberSignature Language="F#" Value="member this.Kty : string" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この検証が適用するキーの種類を示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyType" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />
      </Docs>
    </Member>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public static void Register (Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier verifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Register(class Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier verifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub Register (verifier As JsonWebKeyVerifier)" />
      <MemberSignature Language="F#" Value="static member Register : Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier -&gt; unit" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register verifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="verifier" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier" />
      </Parameters>
      <Docs>
        <param name="verifier">登録を検証します。</param>
        <summary>
            登録の検証機能、<see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />値。
            </summary>
        <remarks>To be added.</remarks>
        <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Kty" />
        <see cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyType" />
        <altmember cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.GetVerifier(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="SurroundWithQuotes">
      <MemberSignature Language="C#" Value="protected static string SurroundWithQuotes (System.Collections.Generic.ICollection&lt;string&gt; items);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig string SurroundWithQuotes(class System.Collections.Generic.ICollection`1&lt;string&gt; items) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.SurroundWithQuotes(System.Collections.Generic.ICollection{System.String})" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function SurroundWithQuotes (items As ICollection(Of String)) As String" />
      <MemberSignature Language="F#" Value="static member SurroundWithQuotes : System.Collections.Generic.ICollection&lt;string&gt; -&gt; string" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.SurroundWithQuotes items" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="items" Type="System.Collections.Generic.ICollection&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="items">To be added.</param>
        <summary>
            二重引用符を含む文字列値を囲むヘルパー メソッドです。 
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <code>"Foo"、「バー」</code>
      </Docs>
    </Member>
    <Member MemberName="ValidateKeyParameterSize">
      <MemberSignature Language="C#" Value="protected static bool ValidateKeyParameterSize (byte[] value, string name, int requiredSize, ref string errorMsg);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig bool ValidateKeyParameterSize(unsigned int8[] value, string name, int32 requiredSize, string&amp; errorMsg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.ValidateKeyParameterSize(System.Byte[],System.String,System.Int32,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function ValidateKeyParameterSize (value As Byte(), name As String, requiredSize As Integer, ByRef errorMsg As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member ValidateKeyParameterSize : byte[] * string * int *  -&gt; bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.ValidateKeyParameterSize (value, name, requiredSize, errorMsg)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="requiredSize" Type="System.Int32" />
        <Parameter Name="errorMsg" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="value">検証する配列。</param>
        <param name="name">エラー メッセージを構築するために使用できる配列名。</param>
        <param name="requiredSize">必要なサイズ (バイト)。</param>
        <param name="errorMsg">エラー メッセージを格納する変数への参照。 メソッドが返された場合のみ設定<code>false</code>です。</param>
        <summary>
            バイト配列のサイズを検証するヘルパー メソッドです。
            </summary>
        <returns>
          <code>true</code>配列は、有効なサイズを場合<code>false otherwise</code>.</returns>
        <remarks>To be added.</remarks>
        <para>有効な配列には、次の条件を満たしています。</para>
        <list type="bullet">
          <item>
            <description><code>null</code>です。</description>
          </item>
          <item>
            <description>長さが少なくとも<paramref name="requiredSize" />; と</description>
          </item>
          <item>
            <description>余分な先頭バイトは、すべてがゼロです。</description>
          </item>
        </list>
      </Docs>
    </Member>
    <Member MemberName="Verify">
      <MemberSignature Language="C#" Value="public bool Verify (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options options, ref string error);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Verify(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options options, string&amp; error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Verify(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
      <MemberSignature Language="F#" Value="member this.Verify : Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options *  -&gt; bool" Usage="jsonWebKeyVerifier.Verify (webKey, options, error)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="options" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options" />
        <Parameter Name="error" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey">確認するインスタンス。</param>
        <param name="options">検証の動作方法を示します。</param>
        <param name="error">検証に失敗した場合に、エラー メッセージを指示する変数への参照。 メソッドが返された場合のみ設定<code>false</code>です。 メソッドを返す場合<code>true</code>、例外がスローまたは、<paramref name="error" />は自分では変更されません。</param>
        <summary>
            指定した JsonWebKey インスタンスを検証します。 
            </summary>
        <returns>
          <code>true</code>JsonWebKey 値は、有効な場合<code>false otherwise</code>です。</returns>
        <remarks>To be added.</remarks>
        <para>検証を調べ、<see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />検証インスタンスを選択するプロパティ (詳細については、次を参照してください。、<see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Register(Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier)" />メソッド)。 見つかった場合は、検証機能は、確認して、キーが、対応するキーの種類に準拠しているかどうかに使用されます。</para>
        <exception cref="T:System.ArgumentNullException">場合、<paramref name="webKey" />パラメーターが null です。</exception>
        <exception cref="T:System.ArgumentException">場合、<paramref name="options" />パラメーターに無効なオプションが含まれています。</exception>
        <exception cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerificationException">JsonWebKey オブジェクトが無効であり、オプション場合<see cref="F:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options.ThrowException" />が指定されました。</exception>
        <altmember cref="T:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options" />
      </Docs>
    </Member>
    <Member MemberName="VerifyByKeyType">
      <MemberSignature Language="C#" Value="public static bool VerifyByKeyType (Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options options, ref string error);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool VerifyByKeyType(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey webKey, valuetype Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier/Options options, string&amp; error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.VerifyByKeyType(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
      <MemberSignature Language="F#" Value="static member VerifyByKeyType : Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options *  -&gt; bool" Usage="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.VerifyByKeyType (webKey, options, error)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.WebKey</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webKey" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="options" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier+Options" />
        <Parameter Name="error" Type="System.String&amp;" RefType="ref" />
      </Parameters>
      <Docs>
        <param name="webKey"></param>
        <param name="options"></param>
        <param name="error"></param>
        <summary>
            インスタンスを検証します指定 JsonWebKey に従って<see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />です。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <see cref="P:Microsoft.Azure.KeyVault.WebKey.JsonWebKey.Kty" />
        <see cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Verify(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
        <altmember cref="M:Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Verify(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.WebKey.JsonWebKeyVerifier.Options,System.String@)" />
      </Docs>
    </Member>
  </Members>
</Type>