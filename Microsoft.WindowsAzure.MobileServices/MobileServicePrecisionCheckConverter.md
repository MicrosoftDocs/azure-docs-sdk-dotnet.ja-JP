<Type Name="MobileServicePrecisionCheckConverter" FullName="Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter">
  <TypeSignature Language="C#" Value="public class MobileServicePrecisionCheckConverter : Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServicePrecisionCheckConverter extends Newtonsoft.Json.JsonConverter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServicePrecisionCheckConverter&#xA;Inherits JsonConverter" />
  <TypeSignature Language="F#" Value="type MobileServicePrecisionCheckConverter = class&#xA;    inherit JsonConverter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.JsonConverter</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            実装<see cref="T:Newtonsoft.Json.JsonConverter" />と共に使用する<see cref="T:System.Int64" />、<see cref="T:System.UInt64" />と<see cref="T:System.Decimal" />値がシリアル化され、サーバーに送信される場合、その精度を確認できるかどうか、値を書き込むだけされるプロパティの種類は失われません。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServicePrecisionCheckConverter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.#ctor" />
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
    <Member MemberName="CanConvert">
      <MemberSignature Language="C#" Value="public override bool CanConvert (Type objectType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool CanConvert(class System.Type objectType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.CanConvert(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function CanConvert (objectType As Type) As Boolean" />
      <MemberSignature Language="F#" Value="override this.CanConvert : Type -&gt; bool" Usage="mobileServicePrecisionCheckConverter.CanConvert objectType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="objectType">確認する型。</param>
        <summary>
            このコンバーターが、指定した型を変換できるかどうかを示します。
            </summary>
        <returns>このコンバーターが、型を変換できるかどうかを示すブール値。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanRead">
      <MemberSignature Language="C#" Value="public override bool CanRead { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool CanRead" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.CanRead" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property CanRead As Boolean" />
      <MemberSignature Language="F#" Value="member this.CanRead : bool" Usage="Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.CanRead" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            これを示す<see cref="T:Newtonsoft.Json.JsonConverter" />逆シリアル化中には使用できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadJson">
      <MemberSignature Language="C#" Value="public override object ReadJson (Newtonsoft.Json.JsonReader reader, Type objectType, object existingValue, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance object ReadJson(class Newtonsoft.Json.JsonReader reader, class System.Type objectType, object existingValue, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.ReadJson(Newtonsoft.Json.JsonReader,System.Type,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ReadJson (reader As JsonReader, objectType As Type, existingValue As Object, serializer As JsonSerializer) As Object" />
      <MemberSignature Language="F#" Value="override this.ReadJson : Newtonsoft.Json.JsonReader * Type * obj * Newtonsoft.Json.JsonSerializer -&gt; obj" Usage="mobileServicePrecisionCheckConverter.ReadJson (reader, objectType, existingValue, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="Newtonsoft.Json.JsonReader" />
        <Parameter Name="objectType" Type="System.Type" />
        <Parameter Name="existingValue" Type="System.Object" />
        <Parameter Name="serializer" Type="Newtonsoft.Json.JsonSerializer" />
      </Parameters>
      <Docs>
        <param name="reader"></param>
        <param name="objectType"></param>
        <param name="existingValue"></param>
        <param name="serializer"></param>
        <summary>
            このコンバーターに対しては、読み取りはサポートされていません。
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteJson">
      <MemberSignature Language="C#" Value="public override void WriteJson (Newtonsoft.Json.JsonWriter writer, object value, Newtonsoft.Json.JsonSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void WriteJson(class Newtonsoft.Json.JsonWriter writer, object value, class Newtonsoft.Json.JsonSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePrecisionCheckConverter.WriteJson(Newtonsoft.Json.JsonWriter,System.Object,Newtonsoft.Json.JsonSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub WriteJson (writer As JsonWriter, value As Object, serializer As JsonSerializer)" />
      <MemberSignature Language="F#" Value="override this.WriteJson : Newtonsoft.Json.JsonWriter * obj * Newtonsoft.Json.JsonSerializer -&gt; unit" Usage="mobileServicePrecisionCheckConverter.WriteJson (writer, value, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="Newtonsoft.Json.JsonWriter" />
        <Parameter Name="value" Type="System.Object" />
        <Parameter Name="serializer" Type="Newtonsoft.Json.JsonSerializer" />
      </Parameters>
      <Docs>
        <param name="writer">
            使用する JsonWriter インスタンス。
            </param>
        <param name="value">
            書き込み時に確認する値。
            </param>
        <param name="serializer">
            現在のシリアライザー。
            </param>
        <summary>
            書き込みます、 <paramref name="value" /> Json 値は、サーバーに送信されるときに有効桁数が失われないことを確認できる場合にのみにします。
            それ以外の場合、例外をスローします。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>