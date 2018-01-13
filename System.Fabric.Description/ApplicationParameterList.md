<Type Name="ApplicationParameterList" FullName="System.Fabric.Description.ApplicationParameterList">
  <TypeSignature Language="C#" Value="public sealed class ApplicationParameterList : System.Collections.ObjectModel.KeyedCollection&lt;string,System.Fabric.Description.ApplicationParameter&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationParameterList extends System.Collections.ObjectModel.KeyedCollection`2&lt;string, class System.Fabric.Description.ApplicationParameter&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationParameterList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationParameterList&#xA;Inherits KeyedCollection(Of String, ApplicationParameter)" />
  <TypeSignature Language="F#" Value="type ApplicationParameterList = class&#xA;    inherit KeyedCollection&lt;string, ApplicationParameter&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.ObjectModel.KeyedCollection&lt;System.String,System.Fabric.Description.ApplicationParameter&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.Fabric.Description.ApplicationParameter</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>アプリケーションの現在のバージョンに適用されるアプリケーションのパラメーターのリストを表します。 使用して取得<see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri)" />です。</para>
      <para>このクラスは、関連付けられている ApplicationParameter の名前は、文字列キーを持つ KeyedCollection から派生します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationParameterList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationParameterList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ApplicationParameterList" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationParameterList (System.Collections.Generic.IEqualityComparer&lt;string&gt; comparer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEqualityComparer`1&lt;string&gt; comparer) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationParameterList.#ctor(System.Collections.Generic.IEqualityComparer{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (comparer As IEqualityComparer(Of String))" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationParameterList : System.Collections.Generic.IEqualityComparer&lt;string&gt; -&gt; System.Fabric.Description.ApplicationParameterList" Usage="new System.Fabric.Description.ApplicationParameterList comparer" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="comparer" Type="System.Collections.Generic.IEqualityComparer&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="comparer">
          <para>等値比較子。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Description.ApplicationParameterList" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationParameterList (System.Collections.Generic.IEqualityComparer&lt;string&gt; comparer, int dictionaryCreationThreshold);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEqualityComparer`1&lt;string&gt; comparer, int32 dictionaryCreationThreshold) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationParameterList.#ctor(System.Collections.Generic.IEqualityComparer{System.String},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (comparer As IEqualityComparer(Of String), dictionaryCreationThreshold As Integer)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationParameterList : System.Collections.Generic.IEqualityComparer&lt;string&gt; * int -&gt; System.Fabric.Description.ApplicationParameterList" Usage="new System.Fabric.Description.ApplicationParameterList (comparer, dictionaryCreationThreshold)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="comparer" Type="System.Collections.Generic.IEqualityComparer&lt;System.String&gt;" />
        <Parameter Name="dictionaryCreationThreshold" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="comparer">
          <para>等値比較子。</para>
        </param>
        <param name="dictionaryCreationThreshold">
          <para>作成のしきい値。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Description.ApplicationParameterList" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyForItem">
      <MemberSignature Language="C#" Value="protected override string GetKeyForItem (System.Fabric.Description.ApplicationParameter item);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string GetKeyForItem(class System.Fabric.Description.ApplicationParameter item) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationParameterList.GetKeyForItem(System.Fabric.Description.ApplicationParameter)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetKeyForItem (item As ApplicationParameter) As String" />
      <MemberSignature Language="F#" Value="override this.GetKeyForItem : System.Fabric.Description.ApplicationParameter -&gt; string" Usage="applicationParameterList.GetKeyForItem item" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="System.Fabric.Description.ApplicationParameter" />
      </Parameters>
      <Docs>
        <param name="item">
          <para>キーを取得する対象のアプリケーション パラメーター。</para>
        </param>
        <summary>
          <para>指定したアプリケーション パラメーターのキーの名前を取得します。</para>
        </summary>
        <returns>
          <para>キー名を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationParameterList.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationParameterList.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            ToString() メソッドをオーバーライドします。
            </summary>
        <returns>
            アプリケーションのすべてのパラメーターとその値を表示する文字列を返します。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>