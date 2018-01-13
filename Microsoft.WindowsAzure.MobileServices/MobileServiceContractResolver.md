<Type Name="MobileServiceContractResolver" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver">
  <TypeSignature Language="C#" Value="public class MobileServiceContractResolver : Newtonsoft.Json.Serialization.DefaultContractResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceContractResolver extends Newtonsoft.Json.Serialization.DefaultContractResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceContractResolver&#xA;Inherits DefaultContractResolver" />
  <TypeSignature Language="F#" Value="type MobileServiceContractResolver = class&#xA;    inherit DefaultContractResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.Serialization.DefaultContractResolver</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <see cref="T:Newtonsoft.Json.Serialization.IContractResolver" />実装で使用される、<see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceClient" />です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceContractResolver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMemberValueProvider">
      <MemberSignature Language="C#" Value="protected override Newtonsoft.Json.Serialization.IValueProvider CreateMemberValueProvider (System.Reflection.MemberInfo member);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Newtonsoft.Json.Serialization.IValueProvider CreateMemberValueProvider(class System.Reflection.MemberInfo member) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.CreateMemberValueProvider(System.Reflection.MemberInfo)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateMemberValueProvider (member As MemberInfo) As IValueProvider" />
      <MemberSignature Language="F#" Value="override this.CreateMemberValueProvider : System.Reflection.MemberInfo -&gt; Newtonsoft.Json.Serialization.IValueProvider" Usage="mobileServiceContractResolver.CreateMemberValueProvider member" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.IValueProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="member" Type="System.Reflection.MemberInfo" />
      </Parameters>
      <Docs>
        <param name="member">メンバー。</param>
        <summary>
            作成、<see cref="T:Newtonsoft.Json.Serialization.IValueProvider" />シリアライザーによって取得およびメンバーから値を設定するために使用します。
            </summary>
        <returns><see cref="T:Newtonsoft.Json.Serialization.IValueProvider" />シリアライザーによって取得およびメンバーから値を設定するために使用します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateObjectContract">
      <MemberSignature Language="C#" Value="protected override Newtonsoft.Json.Serialization.JsonObjectContract CreateObjectContract (Type objectType);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Newtonsoft.Json.Serialization.JsonObjectContract CreateObjectContract(class System.Type objectType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.CreateObjectContract(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateObjectContract (objectType As Type) As JsonObjectContract" />
      <MemberSignature Language="F#" Value="override this.CreateObjectContract : Type -&gt; Newtonsoft.Json.Serialization.JsonObjectContract" Usage="mobileServiceContractResolver.CreateObjectContract objectType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonObjectContract</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="objectType">To be added.</param>
        <summary>
            作成、<see cref="T:Newtonsoft.Json.Serialization.JsonObjectContract" />を JSON に指定された型をシリアル化する方法に関する情報を提供します。
            </summary>
        <returns>
            型の <see cref="T:Newtonsoft.Json.Serialization.JsonObjectContract" />。
            </returns>
        <remarks>
            ある型をキャッチするためにこのメソッドはオーバーライド<see cref="T:System.Runtime.Serialization.DataMemberAttribute" />しなくても 1 つまたは複数のメンバーで、<see cref="T:System.Runtime.Serialization.DataContractAttribute" />型自体にします。 これには、サポートされるために使用されるが、不要になったとこのような型のため、例外をスローする必要があります。 例外を持つ型を正しく属性について開発者に通知、<see cref="T:Newtonsoft.Json.JsonPropertyAttribute" />の代わりに、<see cref="T:System.Runtime.Serialization.DataMemberAttribute" />です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateProperties">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IList&lt;Newtonsoft.Json.Serialization.JsonProperty&gt; CreateProperties (Type type, Newtonsoft.Json.MemberSerialization memberSerialization);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IList`1&lt;class Newtonsoft.Json.Serialization.JsonProperty&gt; CreateProperties(class System.Type type, valuetype Newtonsoft.Json.MemberSerialization memberSerialization) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.CreateProperties(System.Type,Newtonsoft.Json.MemberSerialization)" />
      <MemberSignature Language="F#" Value="override this.CreateProperties : Type * Newtonsoft.Json.MemberSerialization -&gt; System.Collections.Generic.IList&lt;Newtonsoft.Json.Serialization.JsonProperty&gt;" Usage="mobileServiceContractResolver.CreateProperties (type, memberSerialization)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Newtonsoft.Json.Serialization.JsonProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" />
        <Parameter Name="memberSerialization" Type="Newtonsoft.Json.MemberSerialization" />
      </Parameters>
      <Docs>
        <param name="type">
             コレクションを作成する対象となる型<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />インスタンス。
             </param>
        <param name="memberSerialization">
             型のメンバーのシリアル化オプションを指定します。
             </param>
        <summary>
             コレクションを作成<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />指定された型のメンバーのインスタンス。
             </summary>
        <returns>
             コレクション<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />指定された型のメンバーのインスタンス。
             </returns>
        <remarks>
             このメソッドは、型の id プロパティを処理するためにオーバーライドされます。 複数のプロパティ名 (と異なる大文字/小文字の"id") は、すべて id プロパティとして扱われます、ために、型の 1 つだけの id プロパティがあることを確認お必要があります。 また、既定値または null 値であるし、常にシリアル化する必要を JSON に小文字の 'id' 名では、id プロパティを無視するか。
             
             このメソッドもを確認して、適用およびシステム プロパティの属性です。
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateProperty">
      <MemberSignature Language="C#" Value="protected override Newtonsoft.Json.Serialization.JsonProperty CreateProperty (System.Reflection.MemberInfo member, Newtonsoft.Json.MemberSerialization memberSerialization);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Newtonsoft.Json.Serialization.JsonProperty CreateProperty(class System.Reflection.MemberInfo member, valuetype Newtonsoft.Json.MemberSerialization memberSerialization) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.CreateProperty(System.Reflection.MemberInfo,Newtonsoft.Json.MemberSerialization)" />
      <MemberSignature Language="F#" Value="override this.CreateProperty : System.Reflection.MemberInfo * Newtonsoft.Json.MemberSerialization -&gt; Newtonsoft.Json.Serialization.JsonProperty" Usage="mobileServiceContractResolver.CreateProperty (member, memberSerialization)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="member" Type="System.Reflection.MemberInfo" />
        <Parameter Name="memberSerialization" Type="Newtonsoft.Json.MemberSerialization" />
      </Parameters>
      <Docs>
        <param name="member">
            <see cref="T:System.Reflection.MemberInfo" />作成する対象の<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />です。
            </param>
        <param name="memberSerialization">
            メンバーのメンバーのシリアル化オプションを指定します。
            </param>
        <summary>
            作成、<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />の指定された<see cref="T:System.Reflection.MemberInfo" />インスタンス。
            </summary>
        <returns>
            A<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />の指定された<see cref="T:System.Reflection.MemberInfo" />インスタンス。
            </returns>
        <remarks>
            専用に設定するためにこのメソッドはオーバーライド<see cref="T:Newtonsoft.Json.Serialization.IValueProvider" />特定プロパティの種類の実装です。 日付型 (<see cref="T:System.DateTime" />、 <see cref="T:System.DateTimeOffset" />) にシリアル化時に UTC 日付、および逆シリアル化ではローカル日時への変換が必要です。 数値型 (<see cref="T:System.Int64" />、 <see cref="T:System.UInt64" />、 <see cref="T:System.Decimal" />) サーバーでない有効桁数が失われるということを確認するためのチェックを必要とします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveIdProperty">
      <MemberSignature Language="C#" Value="public virtual Newtonsoft.Json.Serialization.JsonProperty ResolveIdProperty (Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Newtonsoft.Json.Serialization.JsonProperty ResolveIdProperty(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.ResolveIdProperty(System.Type)" />
      <MemberSignature Language="F#" Value="abstract member ResolveIdProperty : Type -&gt; Newtonsoft.Json.Serialization.JsonProperty&#xA;override this.ResolveIdProperty : Type -&gt; Newtonsoft.Json.Serialization.JsonProperty" Usage="mobileServiceContractResolver.ResolveIdProperty type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="type">
            Id を取得する対象となる型<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />です。
            </param>
        <summary>
            Id を返します<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />特定の型にします。 <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />指定された型のインスタンスの id 値を取得/設定に使用できます。
            </summary>
        <returns>
            Id<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveProperty">
      <MemberSignature Language="C#" Value="public virtual Newtonsoft.Json.Serialization.JsonProperty ResolveProperty (System.Reflection.MemberInfo member);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Newtonsoft.Json.Serialization.JsonProperty ResolveProperty(class System.Reflection.MemberInfo member) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.ResolveProperty(System.Reflection.MemberInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveProperty (member As MemberInfo) As JsonProperty" />
      <MemberSignature Language="F#" Value="abstract member ResolveProperty : System.Reflection.MemberInfo -&gt; Newtonsoft.Json.Serialization.JsonProperty&#xA;override this.ResolveProperty : System.Reflection.MemberInfo -&gt; Newtonsoft.Json.Serialization.JsonProperty" Usage="mobileServiceContractResolver.ResolveProperty member" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="member" Type="System.Reflection.MemberInfo" />
      </Parameters>
      <Docs>
        <param name="member">
            <see cref="T:System.Reflection.MemberInfo" />を取得する、<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />です。
            </param>
        <summary>
            返します、<see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />の指定された<see cref="T:System.Reflection.MemberInfo" />インスタンス。
            <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />方法に関する情報を取得するために使用できる<see cref="T:System.Reflection.MemberInfo" />シリアル化する必要があります。
            </summary>
        <returns>
            <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />の指定された<see cref="T:System.Reflection.MemberInfo" />インスタンス。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolvePropertyName">
      <MemberSignature Language="C#" Value="protected override string ResolvePropertyName (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string ResolvePropertyName(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.ResolvePropertyName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ResolvePropertyName (propertyName As String) As String" />
      <MemberSignature Language="F#" Value="override this.ResolvePropertyName : string -&gt; string" Usage="mobileServiceContractResolver.ResolvePropertyName propertyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
            解決するプロパティ名。
            </param>
        <summary>
            指定されたプロパティ名を JSON にシリアル化する必要がある名前を返します。
            </summary>
        <returns>
            解決済みのプロパティ名。
            </returns>
        <remarks>
            このメソッドをオーバーライドして、プロパティ名の camel 形式の大文字小文字の区別をサポートします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveSystemProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.MobileServices.MobileServiceSystemProperties ResolveSystemProperties (Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance valuetype Microsoft.WindowsAzure.MobileServices.MobileServiceSystemProperties ResolveSystemProperties(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.ResolveSystemProperties(System.Type)" />
      <MemberSignature Language="F#" Value="abstract member ResolveSystemProperties : Type -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceSystemProperties&#xA;override this.ResolveSystemProperties : Type -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceSystemProperties" Usage="mobileServiceContractResolver.ResolveSystemProperties type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceSystemProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="type">システムのプロパティを取得する対象の型。</param>
        <summary>
            システム プロパティを指定された型のコンマ区切りリストとして返します。 型がサポートされるシステム プロパティをしない場合は null を返します。
            </summary>
        <returns>
            指定された型または型がサポートされるシステム プロパティをしない場合は null のコンマ区切りリストとしてシステム プロパティ。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveTableName">
      <MemberSignature Language="C#" Value="public virtual string ResolveTableName (Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveTableName(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.ResolveTableName(System.Type)" />
      <MemberSignature Language="F#" Value="abstract member ResolveTableName : Type -&gt; string&#xA;override this.ResolveTableName : Type -&gt; string" Usage="mobileServiceContractResolver.ResolveTableName type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="type">
            テーブル名を取得する対象の型。
            </param>
        <summary>
            型のテーブル名を返しますおよび DataContractAttribute、DataTableAttribute のいずれを使用して名前を変更するテーブルのアカウントします。
            </summary>
        <returns>
            テーブル名です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>